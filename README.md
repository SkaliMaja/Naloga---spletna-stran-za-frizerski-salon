# Naloga---spletna-stran-za-frizerski-salon
<!DOCTYPE hrml>
<html lang="en">

<head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>
        Frizerski salon Veter v laseh
    </title>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.1.1/jquery.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
    <style>
        .carousel-inner>.item>img,
        .carousel-inner>.item>a>img {
            width: 70%;
            margin: auto;
        }
    </style>
</head>

<body>
    <div class="container">


        <ul class="nav nav-tabs">
            <li role="presentation" class="active"><a href="#">Domača stran</a></li>
            <li role="presentation"><a href="#">Ekipa</a></li>
            <li role="presentation"><a href="#">Kje nas najdete</a></li>
            <li role="presentation"><a href="#">Naroči se</a></li>
        </ul>

        <div class="page-header">
            <h1>Frizerski salon Veter v laseh <br><small> V našem frizerskem salonu ukrotimo vsak lasek posebej.</small></h1>
        </div>


        <!--carousel    -->

        <div class="container">
            <br>
            <div id="myCarousel" class="carousel slide" data-ride="carousel">
                <!-- Indicators -->
                <ol class="carousel-indicators">
                    <li data-target="#myCarousel" data-slide-to="0" class="active"></li>
                    <li data-target="#myCarousel" data-slide-to="1"></li>
                    <li data-target="#myCarousel" data-slide-to="2"></li>
                    <li data-target="#myCarousel" data-slide-to="3"></li>
                </ol>

                <!-- Wrapper for slides -->
                <div class="carousel-inner" role="listbox">

                    <div class="item active">
                        <img src="https://i.guim.co.uk/img/static/sys-images/Sport/Pix/columnists/2011/5/10/1305034421213/mohican-haircut-007.jpg?w=620&q=20&auto=format&usm=12&fit=max&dpr=2&s=e4c99832bcb80e231683fbbeae37dc78" alt="Irokeza" width="300" height="300">
                        <div class="carousel-caption">
                            <h3>Irokeze</h3>
                            <p>Naj vam zraste greben</p>
                        </div>
                    </div>

                    <div class="item">
                        <img src="http://media3.popsugar-assets.com/files/2011/02/06/4/192/1922664/b1cd5d47a8edc1dd_hearthair/i/Create-Heart-Hair-Braid-Valentine-Day.jpg" alt="Kita" width="300" height="300">
                        <div class="carousel-caption">
                            <h3>Kite</h3>
                            <p>Lepa pričeska ni splet okoliščin.</p>
                        </div>
                    </div>

                    <div class="item">
                        <img src="https://s-media-cache-ak0.pinimg.com/474x/f5/fa/45/f5fa45f3a0167bc57866f3a5f1d8f9e5.jpg" alt="Balin" width="300" height="300">
                        <div class="carousel-caption">
                            <h3>Na balin</h3>
                            <p>Na balin zdaj je IN!</p>
                        </div>
                    </div>

                    <div class="item">
                        <img src="http://cdn.playbuzz.com/cdn/bcf825aa-678c-4a05-8d51-638e3a77f666/c549bba8-a2c5-40e2-8c4d-3a33acbeda4d_560_420.jpg" alt="Barve" width="300" height="300">
                        <div class="carousel-caption">
                            <h3>Barve</h3>
                            <p>Zaradi nas ne dobite sivih las. Lahko pa dobite zelene.</p>
                        </div>
                    </div>

                </div>

                <!-- Left and right controls -->
                <a class="left carousel-control" href="#myCarousel" role="button" data-slide="prev">
                    <span class="glyphicon glyphicon-chevron-left" aria-hidden="true"></span>
                    <span class="sr-only">Prejšnja slika</span>
                </a>
                <a class="right carousel-control" href="#myCarousel" role="button" data-slide="next">
                    <span class="glyphicon glyphicon-chevron-right" aria-hidden="true"></span>
                    <span class="sr-only">Naslednja slika</span>
                </a>
            </div>
        </div>
        <!--  Thumbnails        -->
        <div class="row">
            <div class="col-sm-6 col-md-4 col-xs-2">
                <div class="thumbnail">
                    <img src="http://barber.premiumcoding.com/wp-content/uploads/2013/12/barber-gallery-7.jpg" alt="Barber">
                    <div class="caption">
                        <h3>Kaj lahko naredimo za vas?</h3>
                        <p>Frizerski salon Veter v laseh je specializiran salon za neukrotljive lase. Če ste že čisto obupani, ker se na vaši glavi vedno najde las, ki štrli v napačno smer, pridite k nam in ukrotili ga bomo.</p>
                        <p><a href="#" class="btn btn-primary" role="button">Več o tem</a> </p>

                    </div>
                </div>
            </div>
        </div>
        <!--  Thumbnails        -->
        <div class="row">
            <div class="col-sm-6 col-md-4 col-xs-2">
                <div class="thumbnail">
                    <img src="https://www.gransnet.com/cms/uploads/GN_Images/content/life-and-style/style-and-beauty/beauty/all_hairdressingcollege_shutterstock.jpg" alt="Hairdressers">
                    <div class="caption">
                        <h3>Naša ekipa na delu</h3>
                        <p>Z vsako stranko se posvetuje cela ekipa vrhunskih frizerskih mojstric in mojstrov in skupaj poiščemo rešitev za vsak lasek posebej.</p>
                        <p><a href="#" class="btn btn-primary" role="button">Več o tem</a> </p>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <div class="panel panel-default">
        <!-- Default panel contents -->
        <div class="panel-heading">Naša ekipa</div>
        <div class="panel-body">
            <p>Seznam naših zaposlenih in telefonskih številk, na katerih so dosegljivi.</p>
        </div>

        <!-- Table -->

          <table class="table table-striped table-bordered table-cover">
              <tr>
                  <th>Ime</th>
                  <th>Specializacija</th>
                  <th>Telefon</th>
              </tr>
              <tr>
                  <td>Lasika Strižnik</td>
                  <td>Čopki in kitke</td>
                  <td>01 1234567</td>
              </tr>
              <tr>
                  <td>Čopka Škarnik</td>
                  <td>Frfruji</td>
                  <td>01 1234569</td>
              </tr>
              <tr>
                  <td>Brko Bradnik</td>
                  <td>Brki in brade</td>
                  <td>01 1234568</td>
              </tr>
          </table>


    </div>


    <!-- Button trigger modal -->
    <button type="button" class="btn btn-primary btn-lg" data-toggle="modal" data-target="#myModal">
      Pogoji poslovanja
    </button>

    <!-- Modal -->
    <div class="modal fade" id="myModal" tabindex="-1" role="dialog" aria-labelledby="myModalLabel">
        <div class="modal-dialog" role="document">
            <div class="modal-content">
                <div class="modal-header">
                    <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
                    <h4 class="modal-title" id="myModalLabel">Pogoji</h4>
                </div>
                <div class="modal-body">
                    Stranke se morajo zavedati, da ne moremo sprejeti reklamacij. Ko las odstrižemo, ga ne moremo več dati nazaj.
                </div>
                <div class="modal-footer">
                    <button type="button" class="btn btn-default" data-dismiss="modal">Zapri</button>
                    <button type="button" class="btn btn-primary">Se strinjam</button>
                </div>
            </div>
        </div>
    </div>

    <div>


    </div>
</body>

</html>
