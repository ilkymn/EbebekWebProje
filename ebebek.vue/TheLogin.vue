<template>
    <cx-page-slot position="EbebekSiteLoginMenu" class="EbebekSiteLoginMenu has-components">
         <eb-header-login _nghost-serverapp-c230="">
           <div _ngcontent-serverapp-c230="">
                                <div _ngcontent-serverapp-c230="" class="header__menu account-btn flyout">
                                    <div _ngcontent-serverapp-c230="" class="header__menu-account-dropdown account-btn">
                                        <div _ngcontent-serverapp-c230="" class="header__menu account-btn flyout">
                                            <div _ngcontent-serverapp-c230="" class="header__menu-account-dropdown account-btn">
                                                <cx-page-slot _ngcontent-serverapp-c230="" position="SiteLoginMenu" class="SiteLoginMenu has-components">
                                                <cx-navigation><cx-navigation-ui class="accNavComponent flyout">
                                                    <nav class="defaultBackground" style="z-index: 1002;">
                                                        <span id="lnkMyAccount" tabindex="0">
                                                            <cx-generic-link tabindex="0"><a href="/"> Hesabım </a>
                                                            </cx-generic-link></span>
                                                            <div class="wrapper">
                                                                <div class="childs" depth="1" columns="1">
                                                                    <nav class="orangeBackground">
                                                                        <cx-generic-link tabindex="0">
                                                                            <a id="lnkLoginNavNode" href="/">
                                                                                 Giriş Yap / Hesap Oluştur
                                                                                </a>
                                                                            </cx-generic-link></nav>
                                                                            <nav class="defaultBackground">
                                                                                <cx-generic-link tabindex="0">
                                                                                    <a id="lnkOrderHistoryNavNodeForGuest" href="/">
                                                                                        <img alt="" loading="lazy" src="https://cdn05.e-bebek.com/media/c/siparislerim.png">
                                                                                        <!----> Siparişlerim <!----><!---->
                                                                                    </a><!----><!----><!---->
                                                                                </cx-generic-link>
                                                                                </nav>
                                                                                <nav class="defaultBackground">
                                                                                    <cx-generic-link tabindex="0">
                                                                                        <a id="lnkMessagesNavNodeForGuest" href="/">
                                                                                            <img alt="" loading="lazy" src="https://cdn05.e-bebek.com/media/c/mesaj-logo.png">
                                                                                            <!----> Mesajlarım <!----><!----></a>
                                                                                            
                                                                                        </cx-generic-link></nav>
                                                                                        <nav class="defaultBackground">
                                                                                            <cx-generic-link tabindex="0">
                                                                                                <a id="lnkAssessmentNavNodeForGuest" href="/">
                                                                                                    <img alt="" loading="lazy" src="https://cdn05.e-bebek.com/media/c/degerlendirmelerim-logo.png">
                                                                                                     Değerlendirmelerim </a>
                                                                                                    </cx-generic-link>
                                                                                                </nav>
                                                                                                    <nav class="defaultBackground">
                                                                                                        <cx-generic-link tabindex="0">
                                                                                                            <a id="lnkWishlistNavNodeForGuest" href="/">
                                                                                                                <img alt="" loading="lazy" src="https://cdn05.e-bebek.com/media/c/fav-logo.png">
                                                                                                                <!----> Favorilerim <!----><!----></a>
                                                                                                                </cx-generic-link>
                                                                                                            </nav><!----><!---->
                                                                                                            <nav class="defaultBackground">
                                                                                                                <cx-generic-link tabindex="0">
                                                                                                                    <a id="lnkGiftVoucherNavNodeForGuest" href="/">
                                                                                                                        <img alt="" loading="lazy" src="https://cdn05.e-bebek.com/media/c/hediyelerim-logo.png"><!----> Hediye Çeklerim <!----><!----></a>
                                                                                                                       
                                                                                                                    </cx-generic-link>
                                                                                                                </nav>
                                                                                                            </div></div>
                                                                                                        </nav>
                                                                                                    </cx-navigation-ui></cx-navigation>
                                                                                                </cx-page-slot></div></div>
                                                                                            </div>
                                                                                        </div></div>
                                                                                    </eb-header-login>
                                                                                </cx-page-slot>
                                                                                <cx-page-slot position="MiniCart" class="MiniCart has-components">
                                                                                    
                                                                                    <eb-mini-cart><a class="account-menu-btn" href="/cart"> 
                                                                                        
                                                                                        <span class="mobile-shopping"><i class="icon-shopping-cart"></i></span>
                                                                                    <button id="iconMiniCart" class="my-basket">
                                                                                        <i class="icon-shopping-cart"></i>  SEPETİM </button></a>
                                                                                    </eb-mini-cart>
                                                                                </cx-page-slot>  
</template>