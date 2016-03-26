.markdown-block p {
margin-left:1.5em;
}
.markdown-block .ui-closed:before {
  font-family:monospace;
  content:"+ ";
}

.markdown-block .ui-open:before {
  font-family:monospace;
  content:"- ";
}

<script type="text/javascript" src="//ajax.googleapis.com/ajax/libs/jquery/1/jquery.min.js"></script>
<script>
    $(document).ready(function(){
    $('.markdown-block .sqs-block-content h2').addClass('ui-closed').css('cursor','pointer');
    $(".markdown-block .sqs-block-content h2").nextUntil("h2").slideToggle();
    $(".markdown-block .sqs-block-content h2").click(function() {
      
      $(this).nextUntil("h2").slideToggle();
      $(this).toggleClass('ui-closed ui-open');
      });
    });
    </script>

#F.A.Q.

## + How do I create a ticket?
Please see [this page](Knowledge_Base/Ticket_System.md) for more info!
