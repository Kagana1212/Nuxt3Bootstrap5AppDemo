<template>
<div class="container">
<h1 class="text-center">会計</h1>
<div class="row row-cols-md-2 p-3">
    <NuxtLink
    to="./settlement"
    class="btn btn-outline-danger">年次決算
    </NuxtLink>
    <NuxtLink
    to="./settings"
    class="btn btn-outline-danger">各種設定
    </NuxtLink>
</div>
    <div class="row row-cols-1 row-cols-sm-2 row-cols-md-2">
        <div class="card">
            <div class="card-body">
            <div class="text-center">
            <h3 class="card-title border-bottom border-3 p-2">各種入力</h3>
            <div class="card-text">
            <div class="row row-cols-1">
                <NuxtLink to="./text" class="btn btn-outline-dark m-2">複合仕訳入力</NuxtLink>
                <NuxtLink to="./text" class="btn btn-outline-dark m-2">元帳入力</NuxtLink>
                <NuxtLink to="./text" class="btn btn-outline-dark m-2">通帳入力</NuxtLink>
            </div>
            </div>
            </div>
            </div>
        </div>
        <div class="card">
            <div class="card-body">
            <div class="text-center">
            <h3 class="card-title border-bottom border-3 p-2">各種出力</h3>
            <div class="card-text">
            <div class="row row-cols-1">
                <NuxtLink to="./text" class="btn btn-outline-dark m-2">仕訳帳</NuxtLink>
                <NuxtLink to="./text" class="btn btn-outline-dark m-2">出納帳</NuxtLink>
                <NuxtLink to="./text" class="btn btn-outline-dark m-2">仕訳検索</NuxtLink>
                <NuxtLink to="./text" class="btn btn-outline-dark m-2">総勘定元帳</NuxtLink>
            </div>
            </div>
            </div>
            </div>
        </div>
    </div>
</div>
</template>


