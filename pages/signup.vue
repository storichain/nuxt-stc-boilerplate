<template>
    <section>
        <div class="header mhd">
            <div class="mhd_lg">
                <div class="hd_wrap">
                    <h1 class="ptit"><a href="#">Signup</a></h1>
                    <a href="#" class="btn btn_back_w"><span class="blind">뒤로가기</span></a>
                    <a href="#" class="btn btn_go_home"><span class="blind">홈으로 이동</span></a>
                </div>
            </div>
        </div>

        <div class="container">
            <div class="content">
                <div class="ct_wrap">
                    <h2 class="ct_logo"><img src="/images/logo_txt.png" alt="storichain" /></h2>
                    <form action="">
                        <fieldset>
                            <div class="form_wrap">
                                <div class="form_box">
                                    <h3 class="form_tit">Email ID</h3>
                                    <div class="inp_box"><input type="email" name="" id="email_id" class="inpt" placeholder="Email ID" /><label for="email_id" class="lblt">Email ID</label></div>
                                    <p class="error_msg">error_msg</p>
                                </div>
                                <div class="form_box">
                                    <h3 class="form_tit">Password <span>(more than 8 charactors includes alphabets, digits, symbols)</span></h3>
                                    <div class="inp_box"><input type="password" name="" id="pw" class="inpt" placeholder="Password" /><label for="pw" class="lblt">password</label></div>
                                    <p class="error_msg"></p>
                                </div>
                                <div class="form_box">
                                    <h3 class="form_tit">Password Again</h3>
                                    <div class="inp_box"><input type="password" name="" id="pwa" class="inpt" placeholder="Password" /><label for="pwa" class="lblt">password again</label></div>
                                    <p class="error_msg"></p>
                                </div>
                                <div class="form_box">
                                    <h3 class="form_tit">Profile ID <span>this will be your profile address</span></h3>
                                    <div class="inp_box btn_box"><input type="text" name="" id="profile_id" class="inpt" placeholder="@myid" /><label for="profile_id" class="lblt">Email ID</label><button type="button" class="btn btn_l btn_cb" id="">check</button></div>
                                    <p class="error_msg">error_msg</p>
                                </div>
                                <div class="form_box">
                                    <h3 class="form_tit">Language</h3>
                                    <div class="inp_box">
                                        <select id="language" name="language" title="language" class="sel">
                                            <option value="" selected="">- select -</option>
                                            <option value="0">Korean</option>
                                            <option value="1">English</option>
                                        </select>
                                    </div>
                                </div>
                                <ul class="form_btn form_btn1">
                                    <li><span><button class="btn_r btn_l btn_cp">저장</button></span></li>
                                </ul>
                            </div>
                        </fieldset>
                    </form>
                </div>
            </div>
        </div>

        <div class="footer">
            <p class="copy">copyright &copy; 2018 STORICHAIN ALL RIGHTS RESERVED</p>
            <ul class="cp_lk">
                <li><a href="#">Private policy</a></li>
                <li><a href="#">Terms of Platform</a></li>
                <li><a href="#">Advertise</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
        </div>
    </section>
</template>