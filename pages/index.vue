<template>
    <div>
        <Jumbotron />
        <b-container>
            <b-alert show variant="warning">
                <p class="font-weight-bold">支援のお願い</p>
                <p>
                    このサイトにあるコンテンツは、基本的にはすべて無料で提供されています。<br />
                    今後も無償で提供するため、ぜひご支援をお願いします！
                </p>
                <a href="#donate" class="btn btn-primary">支援する！</a>
            </b-alert>
        </b-container>
        <b-container id="about" class="py-3">
            <h1 class="mb-4">About</h1>
            <p>
                TeamOpenWorldは、巳波みなとが運営するサービスやソフトウェアの総称で、巳波みなとの屋号です。<br />
                巳波みなとをはじめとして、沢山の人やシステムによって支えられています。
            </p>
        </b-container>
        <b-container id="service" class="py-3">
            <h1 class="mb-4">Service</h1>
            <b-card class="my-2">
                <h2 class="h3 font-weight-bold">限界大会</h2>
                <p class="text-muted">クリエイターのための創作企画</p>
                <b-card-text> 毎週開催してる大会企画だよ～ </b-card-text>

                <a
                    href="https://genkai.work"
                    target="_blank"
                    class="btn btn-primary"
                    >公式サイト</a
                >
                <a
                    href="https://twitter.com/genkai_eizo"
                    target="_blank"
                    class="btn btn-primary"
                    >Twitter</a
                >
                <a
                    href="https://genkai-eizo.fanbox.cc/"
                    target="_blank"
                    class="btn btn-warning"
                    >Pixiv Fanbox</a
                >
            </b-card>
        </b-container>
        <b-container id="application" class="py-3">
            <h1 class="mb-4">Application</h1>
            <b-tabs content-class="mt-3">
                <b-tab title="Desktop" active><Software /></b-tab>
                <b-tab title="CLI Tools"><CliTools /></b-tab>
            </b-tabs>
        </b-container>
        <b-container id="community" class="py-3">
            <h1 class="mb-4">Community</h1>
            <b-card class="my-2">
                <h2 class="h3 font-weight-bold">限界創作村</h2>
                <p class="text-muted">クリエイターのための創作企画</p>
                <b-card-text> 毎週開催してる大会企画だよ～ </b-card-text>

                <a href="#" class="card-link">Card link</a>
                <b-link href="#" class="card-link">Another link</b-link>
            </b-card>
            <b-card class="my-2">
                <h2 class="h3 font-weight-bold">Virtual Station</h2>
                <p class="text-muted">クリエイターのための創作企画</p>
                <b-card-text> 毎週開催してる大会企画だよ～ </b-card-text>

                <a href="#" class="card-link">Card link</a>
                <b-link href="#" class="card-link">Another link</b-link>
            </b-card>
        </b-container>
        <b-container id="donate" class="py-3">
            <h1 class="mb-4">Donate</h1>
            <b-row cols="2">
                <b-col>
                    <h2 class="h4">1回だけ支援</h2>
                    <p class="text-muted">
                        1回支援をすることができます。毎月の請求はありません。
                    </p>
                    <b-card class="my-2">
                        <a class="h3 font-weight-bold" href="https://ko-fi.com/minato86" target="_blank">ko-fi</a>
                        <p class="text-muted mt-2 mb-0">対応決済方法: PayPal, クレジットカード</p>
                    </b-card>
                    <b-card class="my-2">
                        <a class="h3 font-weight-bold" href="https://paypal.me/openw?country.x=JP&locale.x=ja_JP" target="_blank">PayPal</a>
                        <p class="text-muted mt-2 mb-0">対応決済方法: PayPal</p>
                    </b-card>
                </b-col>
                <b-col>
                    <h2 class="h4">継続的支援</h2>
                    <p class="text-muted">
                        継続的に支援することができ、自動的に毎月更新されます。<br />
                        ※もちろん途中でやめることができます。
                    </p>
                    <p>
                        継続支援のお礼として、継続支援では限定記事などを配信する場合があります。
                    </p>
                    <b-card class="my-2">
                        <a class="h3 font-weight-bold" href="https://minato86.fanbox.cc/" target="_blank">Pixiv Fanbox</a>
                        <p class="text-muted mt-2 mb-0">対応決済方法: PayPal, クレジットカード, コンビニエンスストア</p>
                    </b-card>
                </b-col>
            </b-row>
        </b-container>
    </div>
</template>

<script></script>
