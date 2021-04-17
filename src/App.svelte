<script>
  let lines = [
    [
      "타비노하지마리와 모-오모이다세나이",
      "키즈이타라 코코니이타",
      "키세츠가 야부케테 미핫켄 세키가이센",
      "칸지루메가 마이고니 나루"
    ],

    [
      "가소쿠우시나우노가 이노치가케노 오모이",
      "타타카우요-니 코이시타",
      "히타스라니 유메오 옷-타",
      "소노호시니 오리타캇-타",
      "키미노소라 토비타캇-타"
    ],
    [
      "다레카 쿠-쿄노린카쿠오 솟토나데테쿠레나이카",
      "무네노고도-니케 토바사레테",
      "코로가리테타 아이노 코토바",
      "다케도 코맛타나 코타에가나이"
    ],
    [
      "슈쿠메이니 하리츠케라레타 홋쿄쿠세이가 모에테루",
      "키미오 다키무싯테 니고라세타",
      "나노니 카렌니 와라우 토코 스키닷타요"
    ],
    [
      "키미가이나이나라 이미난테 나쿠나루카라",
      "히토와 젠부 키에레바이이",
      "아이가 나쿠나레바 코코로닷테 이라나이카라",
      "코노 세카이모 키에테시마에"
    ],
    [
      "즛토 쿠루시캇타",
      "이노치카케노 데아이",
      "토도쿠요-니 유메미타",
      "야미쿠모니 테오노바시타",
      "소노무네니 키키타캇타",
      "키미토 니지 미테타캇타"
    ],
    [
      "다레카 요아케노 칸쇼-데 귯토다이테 쿠레나이카",
      "유메노키도-니 하지카레테 토비치루다케노 아이노나미다",
      "소레가누키다시노 이타미데모 이이"
    ],
    [
      "슈쿠메이니요비모도사레타 홋쿄쿠세이가 나이테루",
      "도-세메이로 이키누쿠나라",
      "키미오 츠키루마데 아이시테 시니타이요"
    ],
    [
      "소시테 하지마루노다",
      "이노치 카케노 오와리",
      "타타카우요-니 아이시타",
      "구샤구샤니 유메오 겟타",
      "소노호시니 하테타캇타",
      "키미노소라 사키타캇타"
    ],
    [
      "다래카 쿠-쿄노 린카쿠오 솟토 나데테쿠레나이카",
      "토키노 하도-니 카키케사레테",
      "스쿠에나캇타 아이노코토바",
      "다카라모-이치도 코타에가호시이"
    ],
    [
      "슈쿠메이니 하리츠케라레타 홋쿄쿠세이가 모에테루",
      "키미오 카키무싯테 니고라세타",
      "나노니 카렌니 와라우 토코 스키닷타요",
      "키미오 카키무싯테 니고라세타",
      "나노니 카렌니 와라우 토코 스키뎃타요"
    ]
  ];
</script>

<style>
  .section,
  .container {
    width: 100%;
    height: 100%;
  }
  /* .section {
    background-color: lightgreen;
  } */
  .container {
    /* background-color: pink; */
    display: flex;
    flex-direction: column;
    flex-wrap: wrap;
    /* align-items: flex-start; */
    align-content: flex-start;
  }
  .aoap_card {
    flex-grow: 0;
    flex-shrink: 0;
    padding: 5px 2px;
    /* background-color: rgba(10, 10, 10, 0.5); */
  }
  .aoap_card p {
    /* padding: 2px; */
    margin: 0;
    padding: 0;
    /* background-color: lightblue; */
    /* font-size: 10pt; */
  }
</style>

<section class="section">
  <div class="container">
    {#each lines as lineCard}
      <div class="aoap_card">
        {#each lineCard as line}
          <p>{line}</p>
        {/each}
      </div>
    {/each}
  </div>
</section>
