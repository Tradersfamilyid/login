# login
user id 
 <!-- start: Content -->
                    <div class="content-wrapper" style="margin-left:0; ">
                        <section class="content">
                                                        <div class="login-front">
    <div class="account-wall">
                                    <div id="login-left" class="loginbox">
                    <div id="title-login">
                        <h3>Traders Family</h3>
                    </div>
                    <a href="https://tradersfamily.asia"><img class="profile-img" src="/components/traders/assets/img/logo-tf.png" alt="LOGO-TF.PNG"></a>
                    <form target="_top" class="form-signin" action="" method="post" onsubmit="loadingIn()">
                        <input type="text" id="logname" class="form-control input-login" placeholder="Email / Username" required name="logname" value="" autofocus>
                        <input type="password" maxlength="12" id="logpass" class="form-control input-login" placeholder="Password" required name="pass" >
                                                <input type="hidden" name="task" value="login">
                        <input type="hidden" name="formkey" value="1234567893feefc5f0q5000bfo0c38d90bbeb">                        <button id="btn-signin" class="btn btn-lg btn-primary btn-block" type="submit"><i class="fa fa-sign-in"></i> &nbsp;Masuk</button>
                        <br>
                        <center><a href=" https://tradersfamily.asia/forgot-password/">Lupa Password?</a></center>
                                            </form>
                    <center>- ATAU -</center>
                    <div id="signin-auth">
                        <button id="btn-loginbymt4" class="btn btn-md btn-success btn-block"><i class="fa fa-line-chart"></i> &nbsp;Masuk menggunakan MT4 Acc.</button>
                    </div>

                    
                </div>
                <!-- /#login-left -->
                                        <div id="login-right" class="loginbox">
                    <div id="title-login">
                        <h3>Daftar Sekarang</h3>
                    </div>
                                        <form target="_top" class="form-signin" action="" method="post" onsubmit="loadingUp()">
                        <label class="control-label">Email <span class="required">*</span></label>
                        <input type="text" class="form-control" value="" name="email" id="email" required placeholder="Email" >
                        <label class="control-label">Nama Lengkap <span class="required">*</span></label>
                        <input type="text" maxlength="25" class="form-control" value="" name="fullname" id="fullname" required placeholder="(4 - 25 karakter)"  style="text-transform:capitalize">
                        <label class="control-label">Password <span class="required">*</span></label>
                        <input type="password" maxlength="12" id="pass1" class="form-control" placeholder="(4 - 12 karakter)" required name="password" value="" >
                        <input type="password" maxlength="12" id="pass2" class="form-control" placeholder="Ulangi Password" required name="password2" value="">
                        <label class="control-label">Telepon <span class="required">*</span></label>
                        <input type="text" class="form-control" value="" name="phone" id="phone" required placeholder="(angka)" onkeyup="numbers_only(this)" >
                        <label class="control-label">Kota Domisili <span class="required">*</span></label>
                                                <div class="loader-in"></div>
                        <select class="kota-select2" name="city" id="city" required style="display:none">
                        </select>
                                                <input type="hidden" name="task" value="register">
                        <input type="hidden" name="formkey" value="7d4c67313331ab1cea422a7d78d4079878247">                        <button id="btn-signup" class="btn btn-lg btn-primary btn-block" type="submit"><i class="fa fa-user-plus"></i> &nbsp;Daftar</button>
                        <br>
                        <div class="social-button-div">
                            <input type="checkbox" name="subscribe" value="1" checked=Checked id="subscribe">
                            <label for="subscribe" style="display:inline;cursor:pointer;"> Saya menyetujui untuk menerima berita terbaru</label><br>
                                                    </div>
                                            </form>
                </div>
                <!-- /#login-right -->
                        </div>
    <!-- /.account-wall -->
</div>
<!-- /.login-front -->

<div class="modal fade" id="loginmt4" tabindex="-1" role="dialog">
    <div class="modal-dialog" role="document">
        <div class="modal-content">
            <div class="modal-header">
                <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span></button>
                <h4 class="modal-title"><i class="fa fa-line-chart"> </i> <b>Masuk menggunakan MT4 Acc.</b></h4>
            </div>
            <div class="row modal-body loading" id="loading" style="display:none">
                <div class="col-lg-12 cont">
                    Please Wait...<br>
                    Connecting to MT4 Server...<br>
                    Login Account...
                    <br>
                    <br>
                    <img src="https://www.tradersfamily.workers.dev/images/ajax-loader.gif" />
                </div>
            </div>
            <form target="_top" method="post" id="mt4login" action="javascript:void(0)">
                <div class="modal-body loginform">
                    <div class="center-block loginmt4">
                        <div class="form-group input-group">
                            <span class="input-group-addon alert-info"><i class="fa fa-server"></i></span>
                            <select name="broker" required class="form-control">
                                <option value="">= Choose Broker =</option>
                                <option value="mrg">Maxrich Group (MRG)</option>
                                <option value="askap">MRG Mega Berjangka (D/H Askap Futures)</option>
                            </select>
                        </div>
                        <div class="form-group input-group">
                            <span class="input-group-addon alert-info"><i class="fa fa-line-chart"></i></span>
                            <input type="text" name="mt4id" placeholder="MT4 Account" required onkeyup="numbers_only(this)" class="form-control">
                        </div>
                        <div class="form-group input-group">
                            <span class="input-group-addon alert-info"><i class="fa fa-key"></i></span>
                            <input type="password" name="paswd" placeholder="Master Password" required class="form-control">
                        </div>
                        <!-- BEGIN: reCAPTCHA v2 implementation - check: https://www.google.com/recaptcha/admin -->
                        <center>
                            <div class="g-recaptcha" data-sitekey="6LdMw-wdAAAAAANiZXOeZ6RURIg5MCKFVPS6q-ZIh"></div>
                        </center><br>
                        <!-- END: reCAPTCHA v2 implementation -->
                        <div class="alert alert-danger"></div>
                    </div>
                </div>
                <div class="modal-footer loginform">
                    <button type="button" class="btn btn-danger" data-dismiss="modal"><i class="fa fa-close"> </i> <b>Cancel</b></button>
                    <button type="submit" class="btn btn-primary"><i class="fa fa-sign-in"> </i> <b>Masuk</b></button>
                </div>
            </form>  
