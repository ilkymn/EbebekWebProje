<template>
    <cx-page-layout _ngcontent-serverapp-c160="" section="logo" class="logo">
    <cx-page-slot position="SiteLogo" class="SiteLogo has-components">
        <eb-banner>
            <cx-generic-link><a href="/">
                <cx-media id="logoEbebek" class="is-initialized">
                    <img src="https://cdn.e-bebek.com/y.ebebek/9973673459742.svg" alt="Ebebek Logo Banner" loading="lazy">
                    </cx-media>
                </a>
            </cx-generic-link>
        </eb-banner>
    </cx-page-slot>
</cx-page-layout>
<div _ngcontent-serverapp-c160="" class="col-xl-6 col-lg-6 header-line-1-search order-3 order-lg-2 order-md-3 order-sm-3">
<cx-page-layout _ngcontent-serverapp-c160="" section="middle" class="middle">
    <cx-page-slot position="SearchBox" class="SearchBox has-components">
        <eb-search-box>
            <div class="header__menu-search">
            <div class="search-wrapper"><img alt="" class="search" src="assets/svg/search.svg">
                <input aria-autocomplete="both" aria-controls="results" aria-describedby="initialDescription" autocomplete="off" id="txtSearchBox" placeholder="Ne aramıştınız? Örnek; yenidoğan giyim, bebek bezi, akülü araba, park yatak" aria-label="Ara">
                <div class="loading"></div>
                <div id="searchContent" role="listbox" class="header__menu-search-content" style="padding-left: 85px;">
                    <div class="header__menu-search-content-suggestion">
                        <div class="row">
                            <div class="header__menu-search-content-buttons no-suggestions-pills">
                                
                           
                        </div>
                    </div>
                 </div>
                 </div>      
                </div>     
            </div>     

</eb-search-box>
                </cx-page-slot>
            </cx-page-layout></div>
            <div _ngcontent-serverapp-c160="" class="col-xl-4 col-lg-3 col-6 header-line-1-account order-2 order-lg-3 order-md-2 order-sm-2">
                <cx-page-layout _ngcontent-serverapp-c160="" section="account" class="account">
                <cx-page-slot position="HeaderWishlist" class="HeaderWishlist has-components">
                    <eb-header-wishlist _nghost-serverapp-c195="">
                        <div _ngcontent-serverapp-c195="" class="header__menu-account-favorite">
                     <a _ngcontent-serverapp-c195="" href="/login"><i _ngcontent-serverapp-c195="" class="icon-favorite" id="iconWishList"></i></a>
                    </div>
                </eb-header-wishlist>

    </cx-page-slot>
    </cx-page-layout>
        </div>
</template>