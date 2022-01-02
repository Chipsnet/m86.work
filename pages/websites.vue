<template>
    <div>
        <b-container class="py-5">
            <h1 class="mb-4 h2">管理サイト一覧</h1>
            <p class="text-muted">
                以下のサイトは巳波みなとによって管理・運営されています。<br />
                これらのドメインへの問い合わせはTeamOpenWorldまでお願いします。
            </p>
            <b-table-simple class="mt-4 text-nowrap" responsive striped>
                <b-thead>
                    <b-tr>
                        <b-th>サイト名</b-th>
                        <b-th>URL</b-th>
                        <b-th>サイト概要</b-th>
                    </b-tr>
                </b-thead>
                <b-tbody>
                    <b-tr v-for="item in items" v-bind:key="item.Url">
                        <b-td>{{ item.Title }}</b-td>
                        <b-td><a :href="item.Url" target="_blank">{{ item.Url }}</a></b-td>
                        <b-td>{{ item.Description }}</b-td>
                    </b-tr>
                </b-tbody>
            </b-table-simple>
        </b-container>
    </div>
</template>

<script>
export default {
    data() {
        return {
            items: [
                {
                    Title: "oreovideo.work",
                    Url: "https://oreovideo.work/",
                    Description:
                        "映像クリエイターおれおさんのポートフォリオサイトです。",
                },
                {
                    Title: "Creators忘年会公式サイト",
                    Url: "https://creatorsbc.fun/",
                    Description: "クリエイターズ忘年会の公式サイトです。"
                },
                {
                    Title: "限界音楽村公式サイト",
                    Url: "https://genkaimusic.com",
                    Description: "限界音楽村の公式サイトです。"
                },
                {
                    Title: "限界大会公式サイト",
                    Url: "https://genkai.work",
                    Description: "限界大会の公式サイトです。"
                }
            ]
        };
    },
};
</script>