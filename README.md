<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.0/css/bootstrap.min.css" integrity="sha384-9gVQ4dYFwwWSjIDZnLEWnxCjeSWFphJiwGPXr1jddIhOegiu1FwO5qRGvFXOdJZ4" crossorigin="anonymous">

<style>
* {
    margin-left: 10px;
}

#csm-header {
  font-family: Papyrus;
}

#csm-header {
  border-style:dotted;
}

#hipster-header {
  background-color:red;
}

#cupcake-header {
  background-color:orange;
}

#pirate-header {
  background-color:yellow;
}

</style>

    <title>CSM Test Site</title>
        <!--INSTALL YOUR SNIPPET HERE-->
        <script>
    (function(apiKey){
        (function(p,e,n,d,o){var v,w,x,y,z;o=p[d]=p[d]||{};o._q=o._q||[];
        v=['initialize','identify','updateOptions','pageLoad','track'];for(w=0,x=v.length;w<x;++w)(function(m){
            o[m]=o[m]||function(){o._q[m===v[0]?'unshift':'push']([m].concat([].slice.call(arguments,0)));};})(v[w]);
            y=e.createElement(n);y.async=!0;y.src='https://cdn.pendo.io/agent/static/'+apiKey+'/pendo.js';
            z=e.getElementsByTagName(n)[0];z.parentNode.insertBefore(y,z);})(window,document,'script','pendo');

            // Call this whenever information about your visitors becomes available
            // Please use Strings, Numbers, or Bools for value types.
            pendo.initialize({
                visitor: {
                    id:              'VISITOR-UNIQUE-ID'   // Required if user is logged in
                    // email:        // Recommended if using Pendo Feedback, or NPS Email
                    // full_name:    // Recommended if using Pendo Feedback
                    // role:         // Optional

                    // You can add any additional visitor level key-values here,
                    // as long as it's not one of the above reserved names.
                },

                account: {
                    id:           'ACCOUNT-UNIQUE-ID' // Highly recommended
                    // name:         // Optional
                    // is_paying:    // Recommended if using Pendo Feedback
                    // monthly_value:// Recommended if using Pendo Feedback
                    // planLevel:    // Optional
                    // planPrice:    // Optional
                    // creationDate: // Optional

                    // You can add any additional account level key-values here,
                    // as long as it's not one of the above reserved names.
                }
            });
    })('b4b565c4-3dc8-4a1a-400d-721f16c3a693');
</script>
  </head>
  <body>

    <h1 id="csm-header">Jess's Best Kept Secrets</h1>
    
    <h2 id="hipster-header">conspiracy theories 101</h2>
 
    <p>JEFFREY EPSTEIN DIDN'T KILL HIMSELF!!!!!!</p>
 
  
    <button id="hipster-button">what's your fav conspiracy theory?</button>

    <h2 id="cupcake-header">cupcaking</h2>
    <p>cupcaking is when a person leaves his or her friends to flirt with someone. It comes from the sweetness of cupcakes and the phrase "being sweet on someone," which is when a person likes someone.</p>
    
    <button id="cupcake-button">sweet</button>

    <h2 id="pirate-header">guess what</h2>
    <p id="pirate-p1">The moon has moonquakes. </p>

    <p id="pirate-p2">The wood frog can hold its pee for up to eight months.</p>
    
    <p id="pirate-p3">Your nostrils work one at a time.</p>
    
    <p id="pirate-p4">Copper door knobs are self-disinfecting.</p>
    
    <p id="pirate-p5">Cotton candy was invented by a dentist.</p>

   
    <button id="pirate-button">ahoy!</button>
    <br>
    <br>
    <iframe src="i-was-framed.html" frameborder="0">
    </iframe>
    <!-- Optional JavaScript -->
    <!-- jQuery first, then Popper.js, then Bootstrap JS -->
    <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.0/umd/popper.min.js" integrity="sha384-cs/chFZiN24E4KMATLdqdvsezGxaGsi4hLGOzlXwp5UZB1LY//20VyM2taTB4QvJ" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.1.0/js/bootstrap.min.js" integrity="sha384-uefMccjFJAIv6A+rW+L4AHf99KvxDjWSu1z9VI8SKNVmz4sk7buKt/6v9KI65qnm" crossorigin="anonymous"></script>
  </body>
</html>
