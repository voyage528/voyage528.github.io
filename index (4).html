<!doctype html>
<html lang="zh">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>🇨🇳🇰🇷 中韩留学生互助站（单文件静态版）</title>
  <style>
    :root{ font-family: system-ui,-apple-system,Segoe UI,Roboto,Arial; color:#111; }
    body{ margin:0; background:#fafafa; }
    a{ color:inherit; text-decoration:none; }
    pre{ margin:0; }

    .topbar{
      position:sticky; top:0; z-index:10;
      display:flex; justify-content:space-between; align-items:center;
      padding:12px 16px; background:#fff; border-bottom:1px solid #eee;
    }
    .left{ display:flex; flex-direction:column; }
    .logo{ font-weight:900; font-size:16px; }
    .sub{ color:#666; font-size:12px; margin-top:2px; }
    .right{ display:flex; gap:10px; align-items:center; flex-wrap:wrap; }

    .container{ max-width:980px; margin:18px auto; padding:0 16px; }

    .card{
      background:#fff; border:1px solid #eee; border-radius:14px;
      padding:14px; margin:12px 0;
    }
    .list{ display:flex; flex-direction:column; gap:12px; }

    .row{ display:flex; gap:10px; align-items:center; }
    .wrap{ flex-wrap:wrap; }
    .spacer{ flex:1; }

    .muted{ color:#666; }
    .small{ font-size:12px; }
    .big{ font-size:18px; font-weight:800; }
    .center{ text-align:center; padding:28px; }

    .btn{
      display:inline-block; padding:8px 12px; border-radius:10px;
      background:#111; color:#fff; border:1px solid #111; cursor:pointer;
    }
    .btn.ghost{ background:#fff; color:#111; border:1px solid #ddd; }
    .btn:active{ transform:translateY(1px); }

    .chip{
      padding:6px 10px; border-radius:999px;
      border:1px solid #ddd; background:#fff; cursor:pointer;
    }
    .chip:active{ transform:translateY(1px); }
    .chip.danger{ border-color:#f1b4b4; background:#fff7f7; }

    .tabs{ display:flex; gap:8px; }
    .tab{
      padding:8px 12px; border-radius:999px;
      border:1px solid #ddd; background:#fff; cursor:pointer;
    }
    .tab.active{ background:#111; color:#fff; border-color:#111; }

    .input,.textarea,select.input{
      width:100%; padding:10px 12px; border-radius:10px;
      border:1px solid #ddd; background:#fff; font-size:14px; box-sizing:border-box;
    }
    .textarea{ resize:vertical; }

    .tag{
      font-size:12px; padding:2px 8px; border-radius:999px;
      background:#f2f2f2; border:1px solid #e8e8e8;
    }
    .h2{ margin:8px 0 6px; font-size:20px; }
    .h3{ margin:0 0 10px; font-size:16px; }
    .section{ margin:14px 0 8px; }
    .preview{ margin-top:8px; color:#333; max-height:44px; overflow:hidden; }

    .content{
      white-space:pre-wrap; font-family:inherit;
      background:#fafafa; border:1px solid #eee;
      padding:10px; border-radius:12px;
    }

    .meta{
      display:grid; grid-template-columns:1fr 1fr;
      gap:8px 14px; font-size:14px;
    }
    @media (max-width:700px){ .meta{ grid-template-columns:1fr; } }

    .grid2{ display:grid; grid-template-columns:1fr 1fr; gap:10px; }
    @media (max-width:700px){ .grid2{ grid-template-columns:1fr; } }

    .label{ font-size:13px; color:#333; font-weight:700; margin-top:6px; }
    .form{ display:grid; gap:10px; }

    .divider{ height:1px; background:#eee; margin:14px 0; }

    .post-card{ cursor:pointer; }
    .post-card:hover{ border-color:#ddd; box-shadow:0 2px 10px rgba(0,0,0,.04); }

    .lang .chip.active{ background:#111; color:#fff; border-color:#111; }

    .modal{
      position:fixed; inset:0;
      background:rgba(0,0,0,.28);
      display:flex; align-items:center; justify-content:center;
      padding:14px; z-index:99;
    }
    .modal-inner{ width:min(820px,100%); }
  </style>
</head>

<body>
  <header class="topbar">
    <div class="left">
      <div class="logo">🇨🇳🇰🇷 <span id="siteName">中韩留学生互助站</span></div>
      <div class="sub" id="siteSub">翻译互助 · 景点推荐（本地存储版）</div>
    </div>

    <div class="right">
      <div class="lang">
        <button class="chip" id="langZh">中文</button>
        <span class="muted">/</span>
        <button class="chip" id="langKo">한국어</button>
      </div>
      <button class="btn" id="btnNewTranslation">+ 发翻译求助</button>
      <button class="btn ghost" id="btnNewTravel">+ 发景点推荐</button>
    </div>
  </header>

  <main class="container">
    <section class="controls card">
      <div class="row wrap">
        <div class="tabs" role="tablist">
          <button class="tab active" data-filter="all" id="tabAll">全部</button>
          <button class="tab" data-filter="translation" id="tabTranslation">翻译求助</button>
          <button class="tab" data-filter="travel" id="tabTravel">景点推荐</button>
        </div>

        <div class="spacer"></div>

        <input class="input" id="search" placeholder="搜索标题/内容/城市/标签…" />
        <button class="chip" id="btnExport">导出</button>
        <button class="chip" id="btnImport">导入</button>
        <button class="chip danger" id="btnReset">清空数据</button>
      </div>

      <div class="muted small" id="tipLine">
        提示：所有数据保存在你的浏览器 localStorage。换电脑/清缓存会丢失，可用“导出/导入”备份。
      </div>
    </section>

    <section id="listView">
      <div id="emptyState" class="card center" style="display:none;">
        <div class="big" id="emptyTitle">还没有帖子</div>
        <div class="muted" id="emptyHint">点击右上角按钮发布第一条吧～</div>
      </div>
      <div id="postList" class="list"></div>
    </section>

    <section id="detailView" style="display:none;">
      <button class="chip" id="btnBack">← 返回</button>

      <article class="card" id="detailCard">
        <div class="row wrap">
          <span class="tag" id="detailKindTag">翻译求助</span>
          <span class="muted" id="detailMeta"></span>
          <span class="spacer"></span>
          <button class="chip danger" id="btnDeletePost">删除</button>
        </div>

        <h2 id="detailTitle" class="h2"></h2>

        <h4 class="section" id="detailInfoTitle">详情信息</h4>
        <pre class="content" id="detailBody"></pre>

        <div id="detailStructured"></div>
      </article>

      <section class="card">
        <h3 class="h3" id="commentsTitle">评论</h3>
        <div id="commentList"></div>

        <div class="divider"></div>

        <h3 class="h3" id="writeCommentTitle">写评论</h3>
        <div class="row wrap">
          <input class="input" id="commentAuthor" placeholder="昵称（可选）" />
        </div>
        <textarea class="textarea" id="commentText" rows="4" placeholder="友好交流～比如：我给你一个更地道的译法..."></textarea>
        <div class="row">
          <button class="btn" id="btnAddComment">提交评论</button>
        </div>
      </section>
    </section>
  </main>

  <div class="modal" id="modal" style="display:none;">
    <div class="modal-inner card">
      <div class="row wrap">
        <h2 class="h2" id="modalTitle">发布</h2>
        <span class="spacer"></span>
        <button class="chip" id="btnCloseModal">✕</button>
      </div>

      <form id="postForm" class="form">
        <input type="hidden" id="kind" />

        <label class="label" id="lblTitle">标题</label>
        <input class="input" id="title" required />

        <label class="label" id="lblBody">详细说明</label>
        <textarea class="textarea" id="body" rows="7" required></textarea>

        <div id="translationFields">
          <div class="grid2">
            <div>
              <label class="label" id="lblSrcLang">原文语言</label>
              <input class="input" id="srcLang" placeholder="中文/한국어/English..." />
            </div>
            <div>
              <label class="label" id="lblTgtLang">目标语言</label>
              <input class="input" id="tgtLang" placeholder="中文/한국어/English..." />
            </div>
          </div>

          <div class="grid2">
            <div>
              <label class="label" id="lblDeadline">截止时间（可选）</label>
              <input class="input" id="deadline" type="datetime-local" />
            </div>
            <div>
              <label class="label" id="lblWordCount">字数（可选）</label>
              <input class="input" id="wordCount" type="number" min="0" step="1" placeholder="500" />
            </div>
          </div>

          <label class="label" id="lblLevel">难度（可选）</label>
          <select class="input" id="level">
            <option value="">-</option>
            <option value="easy" id="optEasy">简单</option>
            <option value="mid" id="optMid">一般</option>
            <option value="hard" id="optHard">困难</option>
          </select>
        </div>

        <div id="travelFields" style="display:none;">
          <label class="label" id="lblCity">城市/地区</label>
          <input class="input" id="city" placeholder="比如：首尔/釜山/济州/北京/上海…" />

          <label class="label" id="lblTags">标签（用逗号分隔）</label>
          <input class="input" id="tags" placeholder="比如：美食, 夜景, 省钱, 博物馆" />

          <div class="grid2">
            <div>
              <label class="label" id="lblBudget">人均预算（可选）</label>
              <input class="input" id="budget" placeholder="比如：人均 80 RMB / 15000 KRW" />
            </div>
            <div>
              <label class="label" id="lblSeason">最佳季节（可选）</label>
              <input class="input" id="season" placeholder="比如：春秋最佳 / 冬天夜景漂亮" />
            </div>
          </div>

          <label class="label" id="lblTransport">交通建议（可选）</label>
          <input class="input" id="transport" placeholder="比如：地铁 2 号线 xx 站步行 10 分钟" />
        </div>

        <div class="row">
          <button class="btn" type="submit" id="btnPublish">发布</button>
          <button class="btn ghost" type="button" id="btnCancel">取消</button>
        </div>

        <div class="muted small" id="formTip">
          提示：这是静态版，数据只保存在本机浏览器里。
        </div>
      </form>
    </div>
  </div>

  <div class="modal" id="importModal" style="display:none;">
    <div class="modal-inner card">
      <div class="row wrap">
        <h2 class="h2" id="importTitle">导入数据</h2>
        <span class="spacer"></span>
        <button class="chip" id="btnCloseImport">✕</button>
      </div>
      <div class="muted small" id="importHint">粘贴导出的 JSON 内容，然后点击导入。</div>
      <textarea class="textarea" id="importText" rows="10" placeholder="粘贴 JSON..."></textarea>
      <div class="row">
        <button class="btn" id="btnDoImport">导入</button>
        <button class="btn ghost" id="btnCancelImport">取消</button>
      </div>
      <div class="muted small" id="importWarn">注意：导入会覆盖当前数据。</div>
    </div>
  </div>

  <script>
    const KEY_DATA = "chkr_help_data_v1";
    const KEY_LANG = "chkr_help_lang_v1";

    const I18N = {
      zh: {
        siteName: "中韩留学生互助站",
        siteSub: "翻译互助 · 景点推荐（本地存储版）",
        all: "全部",
        translation: "翻译求助",
        travel: "景点推荐",
        newTranslation: "+ 发翻译求助",
        newTravel: "+ 发景点推荐",
        searchPh: "搜索标题/内容/城市/标签…",
        export: "导出",
        import: "导入",
        reset: "清空数据",
        tipLine: "提示：所有数据保存在你的浏览器 localStorage。换电脑/清缓存会丢失，可用“导出/导入”备份。",
        emptyTitle: "还没有帖子",
        emptyHint: "点击右上角按钮发布第一条吧～",
        back: "← 返回",
        details: "详情信息",
        comments: "评论",
        writeComment: "写评论",
        submitComment: "提交评论",
        nickPh: "昵称（可选）",
        commentPh: "友好交流～比如：我给你一个更地道的译法...",
        delete: "删除",
        confirmDelete: "确定删除这条帖子吗？（评论也会一起删）",
        confirmReset: "确定清空所有数据吗？这无法恢复。",
        cancelled: "已取消",
        publishTranslation: "发布翻译求助",
        publishTravel: "发布景点推荐",
        title: "标题",
        body: "详细说明",
        publish: "发布",
        cancel: "取消",
        srcLang: "原文语言",
        tgtLang: "目标语言",
        deadline: "截止时间（可选）",
        wordCount: "字数（可选）",
        level: "难度（可选）",
        easy: "简单",
        mid: "一般",
        hard: "困难",
        city: "城市/地区",
        tags: "标签（用逗号分隔）",
        budget: "人均预算（可选）",
        transport: "交通建议（可选）",
        season: "最佳季节（可选）",
        importTitle: "导入数据",
        importHint: "粘贴导出的 JSON 内容，然后点击导入。",
        importWarn: "注意：导入会覆盖当前数据。",
        doImport: "导入",
        badJson: "JSON 格式不正确",
        imported: "导入成功",
        exported: "已导出到剪贴板（若浏览器不允许，会弹出文本框）",
        clipboardFail: "无法自动复制，已弹出文本框，请手动复制。"
      },
      ko: {
        siteName: "중한 유학생 도우미",
        siteSub: "번역 도움 · 관광지 추천 (로컬 저장)",
        all: "전체",
        translation: "번역 도움",
        travel: "관광지 추천",
        newTranslation: "+ 번역 글쓰기",
        newTravel: "+ 여행 글쓰기",
        searchPh: "제목/내용/도시/태그 검색…",
        export: "내보내기",
        import: "가져오기",
        reset: "초기화",
        tipLine: "안내: 데이터는 브라우저 localStorage에 저장됩니다. 기기 변경/캐시 삭제 시 사라질 수 있어요. 내보내기/가져오기로 백업하세요.",
        emptyTitle: "게시글이 없습니다",
        emptyHint: "오른쪽 위 버튼으로 첫 글을 올려보세요!",
        back: "← 뒤로",
        details: "상세 내용",
        comments: "댓글",
        writeComment: "댓글 작성",
        submitComment: "댓글 등록",
        nickPh: "닉네임(선택)",
        commentPh: "예의 있게 대화해요 :) 예: 더 자연스러운 번역을 제안할게요...",
        delete: "삭제",
        confirmDelete: "이 글을 삭제할까요? (댓글도 함께 삭제됩니다)",
        confirmReset: "모든 데이터를 초기화할까요? 되돌릴 수 없습니다.",
        cancelled: "취소됨",
        publishTranslation: "번역 도움 글쓰기",
        publishTravel: "관광지 추천 글쓰기",
        title: "제목",
        body: "상세 내용",
        publish: "게시",
        cancel: "취소",
        srcLang: "원문 언어",
        tgtLang: "목표 언어",
        deadline: "마감 시간(선택)",
        wordCount: "글자 수(선택)",
        level: "난이도(선택)",
        easy: "쉬움",
        mid: "보통",
        hard: "어려움",
        city: "도시/지역",
        tags: "태그(쉼표로 구분)",
        budget: "1인 예산(선택)",
        transport: "교통 팁(선택)",
        season: "추천 시즌(선택)",
        importTitle: "데이터 가져오기",
        importHint: "내보낸 JSON을 붙여넣고 가져오기를 누르세요.",
        importWarn: "주의: 가져오기는 현재 데이터를 덮어씁니다.",
        doImport: "가져오기",
        badJson: "JSON 형식이 올바르지 않습니다",
        imported: "가져오기 성공",
        exported: "클립보드에 복사됨 (불가 시 텍스트 박스가 뜹니다)",
        clipboardFail: "자동 복사 불가. 텍스트 박스에서 수동 복사하세요."
      }
    };

    const $ = (id) => document.getElementById(id);
    const state = { filter:"all", q:"", view:"list", currentId:null };

    function getLang(){
      const v = localStorage.getItem(KEY_LANG);
      return (v==="ko"||v==="zh") ? v : "zh";
    }
    function setLang(lang){
      localStorage.setItem(KEY_LANG, lang);
      applyI18n();
      renderList();
      if (state.view==="detail") renderDetail(state.currentId);
    }
    function tr(key){
      const lang = getLang();
      return (I18N[lang] && I18N[lang][key]) ? I18N[lang][key] : key;
    }

    function nowIso(){ return new Date().toISOString(); }
    function uid(){ return Math.random().toString(36).slice(2,10) + "-" + Date.now().toString(36); }

    function loadData(){
      const raw = localStorage.getItem(KEY_DATA);
      if(!raw){
        const seed={posts:[]};
        localStorage.setItem(KEY_DATA, JSON.stringify(seed));
        return seed;
      }
      try{
        const parsed=JSON.parse(raw);
        if(!parsed.posts) parsed.posts=[];
        return parsed;
      }catch{
        const reset={posts:[]};
        localStorage.setItem(KEY_DATA, JSON.stringify(reset));
        return reset;
      }
    }
    function saveData(data){ localStorage.setItem(KEY_DATA, JSON.stringify(data)); }

    function escapeHtml(s){
      const str = String(s ?? "");
      return str.replaceAll("&","&amp;").replaceAll("<","&lt;").replaceAll(">","&gt;")
                .replaceAll('"',"&quot;").replaceAll("'","&#039;");
    }
    function fmtTime(iso){
      try{ return new Date(iso).toLocaleString(); }catch{ return iso; }
    }
    function kindLabel(kind){ return kind==="travel" ? tr("travel") : tr("translation"); }
    function levelLabel(v){
      if(!v) return "-";
      if(v==="easy") return tr("easy");
      if(v==="mid") return tr("mid");
      if(v==="hard") return tr("hard");
      return v;
    }

    const postList = $("postList");
    const emptyState = $("emptyState");
    const listView = $("listView");
    const detailView = $("detailView");

    const detailKindTag = $("detailKindTag");
    const detailMeta = $("detailMeta");
    const detailTitle = $("detailTitle");
    const detailBody = $("detailBody");
    const detailStructured = $("detailStructured");

    const commentList = $("commentList");
    const commentAuthor = $("commentAuthor");
    const commentText = $("commentText");

    const modal = $("modal");
    const postForm = $("postForm");
    const kindInput = $("kind");
    const titleInput = $("title");
    const bodyInput = $("body");

    const translationFields = $("translationFields");
    const travelFields = $("travelFields");

    const srcLang = $("srcLang");
    const tgtLang = $("tgtLang");
    const deadline = $("deadline");
    const wordCount = $("wordCount");
    const level = $("level");

    const city = $("city");
    const tags = $("tags");
    const budget = $("budget");
    const transport = $("transport");
    const season = $("season");

    const importModal = $("importModal");
    const importText = $("importText");

    function applyI18n(){
      const lang = getLang();
      document.documentElement.lang = (lang==="zh") ? "zh" : "ko";

      $("siteName").textContent = tr("siteName");
      $("siteSub").textContent = tr("siteSub");

      $("tabAll").textContent = tr("all");
      $("tabTranslation").textContent = tr("translation");
      $("tabTravel").textContent = tr("travel");

      $("btnNewTranslation").textContent = tr("newTranslation");
      $("btnNewTravel").textContent = tr("newTravel");

      $("search").placeholder = tr("searchPh");
      $("btnExport").textContent = tr("export");
      $("btnImport").textContent = tr("import");
      $("btnReset").textContent = tr("reset");
      $("tipLine").textContent = tr("tipLine");

      $("emptyTitle").textContent = tr("emptyTitle");
      $("emptyHint").textContent = tr("emptyHint");

      $("btnBack").textContent = tr("back");
      $("detailInfoTitle").textContent = tr("details");
      $("commentsTitle").textContent = tr("comments");
      $("writeCommentTitle").textContent = tr("writeComment");
      $("btnAddComment").textContent = tr("submitComment");
      commentAuthor.placeholder = tr("nickPh");
      commentText.placeholder = tr("commentPh");
      $("btnDeletePost").textContent = tr("delete");

      $("lblTitle").textContent = tr("title");
      $("lblBody").textContent = tr("body");
      $("btnPublish").textContent = tr("publish");
      $("btnCancel").textContent = tr("cancel");

      $("lblSrcLang").textContent = tr("srcLang");
      $("lblTgtLang").textContent = tr("tgtLang");
      $("lblDeadline").textContent = tr("deadline");
      $("lblWordCount").textContent = tr("wordCount");
      $("lblLevel").textContent = tr("level");
      $("optEasy").textContent = tr("easy");
      $("optMid").textContent = tr("mid");
      $("optHard").textContent = tr("hard");
      srcLang.placeholder = "中文/한국어/English...";
      tgtLang.placeholder = "中文/한국어/English...";

      $("lblCity").textContent = tr("city");
      $("lblTags").textContent = tr("tags");
      $("lblBudget").textContent = tr("budget");
      $("lblTransport").textContent = tr("transport");
      $("lblSeason").textContent = tr("season");

      $("langZh").classList.toggle("active", lang==="zh");
      $("langKo").classList.toggle("active", lang==="ko");

      $("importTitle").textContent = tr("importTitle");
      $("importHint").textContent = tr("importHint");
      $("importWarn").textContent = tr("importWarn");
      $("btnDoImport").textContent = tr("doImport");
    }

    function openModal(kind){
      kindInput.value = kind;
      postForm.reset();
      titleInput.value = "";
      bodyInput.value = "";
      level.value = "";

      if(kind==="translation"){
        $("modalTitle").textContent = tr("publishTranslation");
        translationFields.style.display = "";
        travelFields.style.display = "none";
        titleInput.placeholder = tr("phTranslationTitle");
        bodyInput.placeholder = tr("phTranslationBody");
      } else {
        $("modalTitle").textContent = tr("publishTravel");
        translationFields.style.display = "none";
        travelFields.style.display = "";
        titleInput.placeholder = tr("phTravelTitle");
        bodyInput.placeholder = tr("phTravelBody");
      }
      modal.style.display = "flex";
    }
    function closeModal(){ modal.style.display = "none"; }

    function openImport(){
      importText.value = "";
      importModal.style.display = "flex";
    }
    function closeImport(){ importModal.style.display = "none"; }

    function renderList(){
      const data = loadData();
      let posts = [...data.posts].sort((a,b)=>(b.createdAt||"").localeCompare(a.createdAt||""));

      if(state.filter!=="all") posts = posts.filter(p=>p.kind===state.filter);

      const q = (state.q||"").trim().toLowerCase();
      if(q){
        posts = posts.filter(p=>{
          const blob = [p.title,p.body,p.extra?.city,p.extra?.tags,p.extra?.srcLang,p.extra?.tgtLang]
            .filter(Boolean).join(" ").toLowerCase();
          return blob.includes(q);
        });
      }

      postList.innerHTML = "";
      emptyState.style.display = posts.length ? "none" : "block";

      posts.forEach(p=>{
        const card = document.createElement("div");
        card.className = "card post-card";
        card.onclick = ()=>showDetail(p.id);

        let hint="";
        if(p.kind==="translation"){
          const a=p.extra?.srcLang||"-";
          const b=p.extra?.tgtLang||"-";
          hint = `<div class="muted small">${tr("srcLang")}: ${escapeHtml(a)} · ${tr("tgtLang")}: ${escapeHtml(b)}</div>`;
        } else {
          const c=p.extra?.city||"-";
          const tg=p.extra?.tags||"-";
          hint = `<div class="muted small">${tr("city")}: ${escapeHtml(c)} · ${tr("tags")}: ${escapeHtml(tg)}</div>`;
        }

        card.innerHTML = `
          <div class="row wrap">
            <span class="tag">${kindLabel(p.kind)}</span>
            <span class="muted">${fmtTime(p.createdAt)}</span>
          </div>
          <h3 class="h3">${escapeHtml(p.title)}</h3>
          <div class="preview">${escapeHtml(p.body)}</div>
          ${hint}
        `;
        postList.appendChild(card);
      });
    }

    function showList(){
      state.view="list"; state.currentId=null;
      listView.style.display="";
      detailView.style.display="none";
      renderList();
      window.scrollTo({top:0,behavior:"instant"});
    }

    function showDetail(id){
      state.view="detail"; state.currentId=id;
      listView.style.display="none";
      detailView.style.display="";
      renderDetail(id);
      window.scrollTo({top:0,behavior:"instant"});
    }

    function renderDetail(id){
      const data = loadData();
      const post = data.posts.find(p=>p.id===id);
      if(!post){ showList(); return; }

      detailKindTag.textContent = kindLabel(post.kind);
      detailTitle.textContent = post.title;
      detailBody.textContent = post.body;
      detailMeta.textContent = fmtTime(post.createdAt);

      detailStructured.innerHTML = "";
      const box = document.createElement("div");
      box.className = "meta";

      if(post.kind==="translation"){
        box.innerHTML = `
          <div><strong>${tr("srcLang")}:</strong> ${escapeHtml(post.extra?.srcLang || "-")}</div>
          <div><strong>${tr("tgtLang")}:</strong> ${escapeHtml(post.extra?.tgtLang || "-")}</div>
          <div><strong>${tr("deadline")}:</strong> ${escapeHtml(post.extra?.deadline || "-")}</div>
          <div><strong>${tr("wordCount")}:</strong> ${escapeHtml(post.extra?.wordCount ?? "-")}</div>
          <div><strong>${tr("level")}:</strong> ${escapeHtml(levelLabel(post.extra?.level) || "-")}</div>
        `;
      } else {
        box.innerHTML = `
          <div><strong>${tr("city")}:</strong> ${escapeHtml(post.extra?.city || "-")}</div>
          <div><strong>${tr("tags")}:</strong> ${escapeHtml(post.extra?.tags || "-")}</div>
          <div><strong>${tr("budget")}:</strong> ${escapeHtml(post.extra?.budget || "-")}</div>
          <div><strong>${tr("season")}:</strong> ${escapeHtml(post.extra?.season || "-")}</div>
          <div><strong>${tr("transport")}:</strong> ${escapeHtml(post.extra?.transport || "-")}</div>
        `;
      }

      const section = document.createElement("div");
      section.className = "section";
      section.textContent = kindLabel(post.kind);
      detailStructured.appendChild(section);
      detailStructured.appendChild(box);

      renderComments(post);

      $("btnDeletePost").onclick = ()=>{
        if(!confirm(tr("confirmDelete"))) return;
        const next = loadData();
        next.posts = next.posts.filter(p=>p.id!==id);
        saveData(next);
        showList();
      };
    }

    function renderComments(post){
      commentList.innerHTML = "";
      const comments = post.comments || [];
      if(!comments.length){
        const empty = document.createElement("div");
        empty.className = "muted small";
        empty.textContent = tr("no_comments") || "";
        commentList.appendChild(empty);
        return;
      }
      comments.sort((a,b)=>(a.createdAt||"").localeCompare(b.createdAt||""));
      comments.forEach(c=>{
        const card = document.createElement("div");
        card.className = "card";
        const author = c.author ? escapeHtml(c.author) : "Anon";
        card.innerHTML = `
          <div class="row wrap">
            <strong>${author}</strong>
            <span class="muted small">${fmtTime(c.createdAt)}</span>
            <span class="spacer"></span>
            <button class="chip danger" data-cid="${c.id}">${tr("delete")}</button>
          </div>
          <div>${escapeHtml(c.content)}</div>
        `;
        const delBtn = card.querySelector("button[data-cid]");
        delBtn.onclick = ()=>{
          const next = loadData();
          const p = next.posts.find(x=>x.id===post.id);
          if(!p) return;
          p.comments = (p.comments||[]).filter(x=>x.id!==c.id);
          saveData(next);
          renderDetail(post.id);
        };
        commentList.appendChild(card);
      });
    }

    document.addEventListener("DOMContentLoaded", ()=>{
      applyI18n();

      $("langZh").onclick = ()=>setLang("zh");
      $("langKo").onclick = ()=>setLang("ko");

      document.querySelectorAll(".tab").forEach(btn=>{
        btn.onclick = ()=>{
          document.querySelectorAll(".tab").forEach(x=>x.classList.remove("active"));
          btn.classList.add("active");
          state.filter = btn.dataset.filter;
          renderList();
        };
      });

      $("search").addEventListener("input", ()=>{
        state.q = $("search").value || "";
        renderList();
      });

      $("btnNewTranslation").onclick = ()=>openModal("translation");
      $("btnNewTravel").onclick = ()=>openModal("travel");

      $("btnCloseModal").onclick = closeModal;
      $("btnCancel").onclick = ()=>{ closeModal(); alert(tr("cancelled")); };
      modal.addEventListener("click", (e)=>{ if(e.target===modal) closeModal(); });

      postForm.onsubmit = (e)=>{
        e.preventDefault();
        const kind = kindInput.value;

        const title = titleInput.value.trim();
        const body = bodyInput.value.trim();
        if(title.length < 3){ alert(tr("title_short") || "Title too short"); return; }
        if(body.length < 10){ alert(tr("body_short") || "Body too short"); return; }

        const data = loadData();
        const post = { id: uid(), kind, title, body, createdAt: nowIso(), extra:{}, comments:[] };

        if(kind==="translation"){
          post.extra.srcLang = srcLang.value.trim() || "";
          post.extra.tgtLang = tgtLang.value.trim() || "";
          post.extra.deadline = deadline.value || "";
          const wc = $("wordCount").value ? Number($("wordCount").value) : "";
          post.extra.wordCount = Number.isFinite(wc) ? wc : "";
          post.extra.level = level.value || "";
        } else {
          post.extra.city = city.value.trim() || "";
          post.extra.tags = tags.value.trim() || "";
          post.extra.budget = budget.value.trim() || "";
          post.extra.transport = transport.value.trim() || "";
          post.extra.season = season.value.trim() || "";
        }

        data.posts.push(post);
        saveData(data);
        closeModal();
        showDetail(post.id);
      };

      $("btnBack").onclick = showList;

      $("btnAddComment").onclick = ()=>{
        const id = state.currentId;
        if(!id) return;

        const author = (commentAuthor.value||"").trim();
        const content = (commentText.value||"").trim();
        if(content.length < 2){ alert(tr("comment_short") || "Too short"); return; }

        const data = loadData();
        const post = data.posts.find(p=>p.id===id);
        if(!post) return;

        post.comments = post.comments || [];
        post.comments.push({ id: uid(), author, content, createdAt: nowIso() });
        saveData(data);

        commentText.value = "";
        renderDetail(id);
      };

      $("btnExport").onclick = async ()=>{
        const data = loadData();
        const json = JSON.stringify(data, null, 2);
        try{
          await navigator.clipboard.writeText(json);
          alert(tr("exported"));
        }catch{
          alert(tr("clipboardFail"));
          prompt("Copy JSON:", json);
        }
      };

      $("btnImport").onclick = openImport;
      $("btnCloseImport").onclick = closeImport;
      $("btnCancelImport").onclick = closeImport;
      importModal.addEventListener("click", (e)=>{ if(e.target===importModal) closeImport(); });

      $("btnDoImport").onclick = ()=>{
        const raw = importText.value.trim();
        try{
          const parsed = JSON.parse(raw);
          if(!parsed || !Array.isArray(parsed.posts)) throw new Error("bad shape");
          saveData(parsed);
          closeImport();
          showList();
          alert(tr("imported"));
        }catch{
          alert(tr("badJson"));
        }
      };

      $("btnReset").onclick = ()=>{
        if(!confirm(tr("confirmReset"))) return;
        saveData({posts:[]});
        showList();
      };

      showList();
    });
  </script>
</body>
</html>
