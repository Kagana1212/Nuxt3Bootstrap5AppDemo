<template>
<div class="container">
<h1 class="text-center">会計</h1>
<div class="row row-cols-md-2 p-3">
<div class="sample-link-area">
    <h3 class="btn btn-primary btn-lg" href="/settlement.vue" role="button">年次決算</h3>
</div>
<div class="sample-link-area">
    <button v-on:click>各種設定</button>
</div>
</div>
    <div class="row row-cols-1 row-cols-sm-2 row-cols-md-2">
        <div class="card mb-3">
            <div class="card-body">
            <div class=text-center>
            <h3 class="card-title border-bottom border-3 p-2">各種入力</h3>
            <div class="card-text">
                <p>複合仕訳入力</p>
                <p>元帳入力</p>
                <p>通帳入力</p>
            </div>
            </div>
            </div>
        </div>
        <div class="card mb-3">
            <div class="card-body">
            <div class=text-center>
            <h3 class="card-title border-bottom border-3 p-2">各種出力</h3>
            <div class="card-text">
                <p>仕訳帳</p>
                <p>出納帳</p>
                <p>仕訳検索</p>
                <p>総勘定元帳</p>
            </div>
            </div>
            </div>
        </div>
    </div>
</div>
</template>

