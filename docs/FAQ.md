<script src="//ajax.googleapis.com/ajax/libs/jquery/1/jquery.min.js"></script>
 <script>
     $(document).ready(function(){
     $('.markdown-block .sqs-block-content h2').css('cursor','pointer');
     $(".markdown-block .sqs-block-content h2").nextUntil("h2").slideToggle();
     $(".markdown-block .sqs-block-content h2").click(function() {$(this).nextUntil("h2").slideToggle();});
     });
     </script>
     
#F.A.Q.

## + How do I create a ticket?
Please see [this page](Knowledge_Base/Ticket_System.md) for more info!
