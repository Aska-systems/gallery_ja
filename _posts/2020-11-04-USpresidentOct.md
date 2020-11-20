---
layout: post
title:  "アメリカ大統領選挙 2020 (10月)"
img: 2020_USpresident/USpoll2020.jpg
---

大統領ディベート最終回（10/22）の後に実施された調査です。

<div class="jumbotron">
  <h4>What is the most important issue to you personally in the upcoming election?</h4>
</div>

| Summary | |
|------|------|
| Period | Oct. 26th -- 30th, 2020 |
| Num. of respondents | 278 |
| Num. of opinions | 177 |
| Num. of initial opinions | 0 |
| Platform | MTurk (US residents) |
{: .table .table-striped .table-hover}

<br>

## 回答パターン
**Circular palette diagram**

<img src="{{site.baseurl}}/images/2020_USpresident/October/circular_palette_diagram.png" alt="fig_circular_palette"
style = "
  width: 600px;
  border: none;
  background: none;
  margin: 1% 1% 1% 1%;
  text-align: center;
  display: inline-block;
">

**Linear palette diagram**

<img src="{{site.baseurl}}/images/2020_USpresident/October/linear_palette_diagram.png" alt="fig_group_size"
style = "
  width: 600px;
  border: none;
  background: none;
  margin: 1% 1% 1% 10%;
  text-align: center;
  display: inline-block;
">

上の図は、パレットダイアグラムという図で、各回答者の回答パターンを可視化したものです。
円形のパレットダイアグラムでは、回答者が極方向に並べられ、回答パターンが動径方向に記されています。
もう一つのパレットダイアグラムでは、回答者が横一列に並べられ、回答パターンが縦軸方向に記されています。
パレットダイアグラムに関する詳細は[こちら](https://github.com/palette-diagram/palette-diagram)をご覧ください。


**技術的なポイント**
- このデータは、投票クラスタリング（英語名Aska）によって収集されました。これによって、意見グラフが生成されます。
- 回答意見は、回答パターンに基づいてグラフ分割によって分類されています[^1]。
- グループラベル（コーディング）は、意見グループの回答文章に基づいて、我々が付与したものです。
- この分析ではアノテーションはしておりません。意味が重複したグループ(*Economy* and *COVID-19 & Economy*)やいくつか分類ミスがあるのはそのためです。

[^1]: この分類を見て、「おかしい」と思われた方がいるかもしれません。実は、収集した回答の数自体は278件よりも多く、それらの情報（といくつかの"テクニック"）によって今回の分類を実現しています。


<br>


## 各意見グループ内の回答
以下では、それぞれの意見グループで、支持の多かった回答をリストしています。

<div class="card">
  <div class="card-header">
  Healthcare (25 posts)
  </div>
  <ul class="list-group list-group-flush">
  <li class="list-group-item">
    The most important to me is letting the president do his job. Parties working together. Accepting the results! Not destroying cities when you don't get your way.
    <br><span class="badge badge-dark">17 likes</span>
  </li>
  <li class="list-group-item">
    Some sort of health care reform to make it more affordable.
    <br><span class="badge badge-dark">14 likes</span>
  </li>
  <li class="list-group-item">
    The most important issue is access to affordable healthcare
    <br><span class="badge badge-dark">13 likes</span>
  </li>
  <div class="collapse" id="collapseExample0">
  <li class="list-group-item">
    Healthcare is the most important issue in the upcoming election. I have a pre-existing condition, a daughter who is covered under my policy but is now 23 years old and I have concern for siblings, family members and friends. 
    <br><span class="badge badge-dark">13 likes</span>
  </li>
  <li class="list-group-item">
    Healthcare reform and access
    <br><span class="badge badge-dark">13 likes</span>
  </li>
  <li class="list-group-item">
    Universal healthcare.
    <br><span class="badge badge-dark">13 likes</span>
  </li>
  <li class="list-group-item">
    Protecting health care and the affordable care act
    <br><span class="badge badge-dark">12 likes</span>
  </li>
  <li class="list-group-item">
    Change the president and change America
    <br><span class="badge badge-dark">11 likes</span>
  </li>
  <li class="list-group-item">
    climate change
    <br><span class="badge badge-dark">10 likes</span>
  </li>
  <li class="list-group-item">
    Improving basic human rights issues like health, nourishment, housing, and education.
    <br><span class="badge badge-dark">10 likes</span>
  </li>
  </div>
  <button class="btn btn-light btn-block" type="button" data-toggle="collapse" data-target="#collapseExample0" aria-expanded="false" aria-controls="collapseExample0">
    See more
  </button>
  </ul>
</div>

<div class="card">
  <div class="card-header">
  Economy (5 posts)
  </div>
  <ul class="list-group list-group-flush">
  <li class="list-group-item">
    Reopening and stabilizing the economy. Getting employment numbers back up. 
    <br><span class="badge badge-dark">12 likes</span>
  </li>
  <li class="list-group-item">
    I SUPPORT ALL THE RESPONSES FIRST THE PEOPLE AND THE ECONOMY HAS TO BE OPEN NORMAL AND MORE JOBS HERE IN FLORIDA THE MINIMUN WAGE
    <br><span class="badge badge-dark">5 likes</span>
  </li>
  <li class="list-group-item">
    The most important issue in the upcoming election is the economy. 
    <br><span class="badge badge-dark">4 likes</span>
  </li>
  <div class="collapse" id="collapseExample1">
  <li class="list-group-item">
    Income Inequality
    <br><span class="badge badge-dark">0 likes</span>
  </li>
  <li class="list-group-item">
    My most important issue is the current economy. 
    <br><span class="badge badge-dark">0 likes</span>
  </li>
  </div>
  <button class="btn btn-light btn-block" type="button" data-toggle="collapse" data-target="#collapseExample1" aria-expanded="false" aria-controls="collapseExample1">
    See more
  </button>
  </ul>
</div>

<div class="card">
  <div class="card-header">
  COVID-19 & Economy (75 posts)
  </div>
  <ul class="list-group list-group-flush">
  <li class="list-group-item">
    Covid-19 Relief 
    <br><span class="badge badge-dark">38 likes</span>
  </li>
  <li class="list-group-item">
    Economy
    <br><span class="badge badge-dark">33 likes</span>
  </li>
  <li class="list-group-item">
    Covid-19 measures.
    <br><span class="badge badge-dark">30 likes</span>
  </li>
  <div class="collapse" id="collapseExample2">
  <li class="list-group-item">
    The most important issue to me is re-opening the economy and getting back to our normal lives.
    <br><span class="badge badge-dark">23 likes</span>
  </li>
  <li class="list-group-item">
    bringing back the economy to what it was pre covid-19
    <br><span class="badge badge-dark">21 likes</span>
  </li>
  <li class="list-group-item">
    Our healthcare and for those with pre-existing conditions 
    <br><span class="badge badge-dark">19 likes</span>
  </li>
  <li class="list-group-item">
    Healthcare coverage for all Americans to help us through the pandemic and beyond.
    <br><span class="badge badge-dark">19 likes</span>
  </li>
  <li class="list-group-item">
    Coronavirus crises
    <br><span class="badge badge-dark">19 likes</span>
  </li>
  <li class="list-group-item">
    Solve Covid and preventing further sickness.
    <br><span class="badge badge-dark">19 likes</span>
  </li>
  <li class="list-group-item">
    Preserving the rights of the individual. 
    <br><span class="badge badge-dark">18 likes</span>
  </li>
  </div>
  <button class="btn btn-light btn-block" type="button" data-toggle="collapse" data-target="#collapseExample2" aria-expanded="false" aria-controls="collapseExample2">
    See more
  </button>
  </ul>
</div>

<div class="card">
  <div class="card-header">
  Racial equality (11 posts)
  </div>
  <ul class="list-group list-group-flush">
  <li class="list-group-item">
    Racial equality
    <br><span class="badge badge-dark">18 likes</span>
  </li>
  <li class="list-group-item">
    Reduce the taxes
    <br><span class="badge badge-dark">9 likes</span>
  </li>
  <li class="list-group-item">
    Social justice issues
    <br><span class="badge badge-dark">7 likes</span>
  </li>
  <div class="collapse" id="collapseExample3">
  <li class="list-group-item">
    ANY PARTY WILL BUT THE MAIN THING IS THE WORLD BECAME NORMAL
    <br><span class="badge badge-dark">4 likes</span>
  </li>
  <li class="list-group-item">
    criminal justice reform, specifically being more lenient on laws and prevent prison overcrowding
    <br><span class="badge badge-dark">4 likes</span>
  </li>
  <li class="list-group-item">
    Stopping the race-baiting and division of the population
    <br><span class="badge badge-dark">4 likes</span>
  </li>
  <li class="list-group-item">
    Equality. Justice. A president who doesn't give handouts but also had a heart
    <br><span class="badge badge-dark">4 likes</span>
  </li>
  <li class="list-group-item">
    Decency, ending racism and bringing the country together.
    <br><span class="badge badge-dark">3 likes</span>
  </li>
  <li class="list-group-item">
    Violence in the streets. 
    <br><span class="badge badge-dark">1 likes</span>
  </li>
  <li class="list-group-item">
    Some one with a moral compass. 
    <br><span class="badge badge-dark">1 likes</span>
  </li>
  </div>
  <button class="btn btn-light btn-block" type="button" data-toggle="collapse" data-target="#collapseExample3" aria-expanded="false" aria-controls="collapseExample3">
    See more
  </button>
  </ul>
</div>

<div class="card">
  <div class="card-header">
  Climate change, Women's rights, etc. (61 posts)
  </div>
  <ul class="list-group list-group-flush">
  <li class="list-group-item">
    The corruption and lawlessness of the current administration. 
    <br><span class="badge badge-dark">15 likes</span>
  </li>
  <li class="list-group-item">
    Immigration
    <br><span class="badge badge-dark">15 likes</span>
  </li>
  <li class="list-group-item">
    Hunger, homelessness, and affordable housing
    <br><span class="badge badge-dark">11 likes</span>
  </li>
  <div class="collapse" id="collapseExample4">
  <li class="list-group-item">
    Climate change solutions, not denials
    <br><span class="badge badge-dark">11 likes</span>
  </li>
  <li class="list-group-item">
    Women's rights/pro-choice
    <br><span class="badge badge-dark">10 likes</span>
  </li>
  <li class="list-group-item">
    abortion and reproductive rights 
    <br><span class="badge badge-dark">10 likes</span>
  </li>
  <li class="list-group-item">
    covid and harm reduction from conservatives 
    <br><span class="badge badge-dark">10 likes</span>
  </li>
  <li class="list-group-item">
    Equal rights for women
    <br><span class="badge badge-dark">9 likes</span>
  </li>
  <li class="list-group-item">
    Corruption actually being addressed and nepotism laws being enforced. The fact that Trump has funneled millions into his own businesses and contacts at the tax payers expense is out of line and He should have sold off Mar-a-lag
    <br><span class="badge badge-dark">9 likes</span>
  </li>
  <li class="list-group-item">
    Climate change.
    <br><span class="badge badge-dark">9 likes</span>
  </li>
  </div>
  <button class="btn btn-light btn-block" type="button" data-toggle="collapse" data-target="#collapseExample4" aria-expanded="false" aria-controls="collapseExample4">
    See more
  </button>
  </ul>
</div>



