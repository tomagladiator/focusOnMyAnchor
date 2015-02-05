# focusOnMyAnchor
Tiny jQuery making a huge difference in Accessibility. You will have a bulletproof focus on an element of your page.

First, add this script on you website (with jQuery)

      $('.focusOnMyAnchor').click(function () {
        var myAnchor = $(this).attr('href');
        $(''+myAnchor+'').attr('tabIndex', '0');
        $(''+myAnchor+'').focus();
      });
      
Then, add the class 'focusOnMyAnchor' on all link with an anchor.

Tadaaa, you can now navigate throw your website with the TAB key, perfect for accessibility!
