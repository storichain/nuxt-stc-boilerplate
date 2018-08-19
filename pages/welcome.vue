<template>
    <section>
        <div class="header mhd">
            <div class="mhd_lg">
                <div class="hd_wrap">
                    <h1 class="ptit"><a href="#">Welcome</a></h1>
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
                            <div class="welcome_wrap">
                                <h2 class="welcome_tit">Welcome!</h2>
                                <div class="welcome_ct">
                                    <p class="welcome_txt1">Now, you can creat, sell, trade, <br />fund stories assets</p>
                                    <h3 class="choose">Choose Your User Role</h3>
                                    <ul class="choose_lst">
                                        <li><span><input type="radio" id="storyteller" name="choose" value="" checked="checked"><label id="stLb" for="storyteller">Storyteller</label></span></li>
                                        <li><span><input type="radio" id="reader" name="choose" value=""><label id="stLb" for="reader">Reader</label></span></li>
                                        <li><span><input type="radio" id="pd" name="choose" value=""><label id="stLb" for="pd">PD</label></span></li>
                                    </ul>
                                    <p class="welcome_txt2">Check your email <a href="mailto:joyce@gmail.com">(joyce@gmail.com)</a><br /> and click the registration link.</p>
                                    <p class="welcome_txt3">the registration linke validates 7 days only.</p>
                                    <p class="welcome_txt4">check the spam mail box too</p>
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
    </section>
</template>