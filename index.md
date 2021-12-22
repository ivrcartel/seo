<!doctype html>
<html lang="tr">
    <head>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <title>Jquery Örnekleri- yazilimbilisim.net</title>
        <link href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css" rel="stylesheet">
      
    </head>
    <body>
        <div class="container">
        <div class="row">
            <div class="col-md-12 col-sm-12 col-xs-12">
                <h1>Jquery Örnekleri</h1>
            </div> 
        </div>
        <div class="row">
            <div class="col-md-12 col-sm-12 col-xs-12">
                <h1 class="alert-info" id="zemin">mesaj</h1>
            </div>
        </div>
        
        
        <script  src="https://code.jquery.com/jquery-3.2.1.js"  integrity="sha256-DZAnKJ/6XZ9si04Hgrsxu/8s717jcIzLy3oi35EouyE=" crossorigin="anonymous"></script>
        <script>
            //belge yüklendikten sonra çalıştırılacağını söyler
            $(function(){
                /*
                id değeri zemin olan nesnenin 
                içine merhaba dünya yaz
                */
                $('#zemin').html('merhaba dünya');           
            });
        </script>
        </div>
    </body>
</html>
