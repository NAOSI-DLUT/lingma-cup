<template>
  <div
    class="min-h-screen bg-gradient-to-br from-slate-900 via-purple-900 to-slate-900 dark:bg-gradient-to-br dark:from-gray-900 dark:via-indigo-950 dark:to-black transition-colors duration-300"
  >
    <!-- Header -->
    <header class="bg-white dark:bg-gray-800 shadow-sm">
      <div class="container mx-auto px-4 py-4">
        <h1
          class="text-2xl md:text-3xl font-bold text-blue-600"
        >
          大连理工大学第一届Vibe Coding Hackathon "灵码杯"
        </h1>
        <nav class="mt-4 flex flex-wrap gap-4">
          <a
            href="#event-info"
            class="text-blue-600 hover:text-blue-700 transition-colors flex items-center"
          >
            <div class="i-ri-information-line mr-1"></div>
            活动详情
          </a>
          <a
            href="#schedule"
            class="text-blue-600 hover:text-blue-700 transition-colors flex items-center"
          >
            <div class="i-ri-calendar-line mr-1"></div>
            赛程安排
          </a>
          <a
            href="#awards"
            class="text-blue-600 hover:text-blue-700 transition-colors flex items-center"
          >
            <div class="i-ri-trophy-line mr-1"></div>
            奖项设置
          </a>
          <a
            href="#register"
            class="text-blue-600 hover:text-blue-700 transition-colors flex items-center"
          >
            <div class="i-ri-edit-line mr-1"></div>
            立即报名
          </a>
        </nav>
      </div>
    </header>

    <!-- Hero Section -->
    <section
      class="bg-gradient-to-r from-blue-500 to-cyan-400 dark:from-blue-700 dark:to-cyan-600 text-white py-12"
    >
      <div class="container mx-auto px-4 text-center">
        <h2 class="text-3xl md:text-4xl font-bold mb-4">
          依托通义灵码，开启智能编程新时代
        </h2>
        <p class="text-lg md:text-xl max-w-3xl mx-auto mb-8">
          通过本次大赛，掌握AI工具的核心应用方法，培养智能化开发趋势下的复合型人才
        </p>
        <a
          href="#register"
          class="inline-block bg-white text-blue-600 hover:bg-blue-50 dark:bg-gray-800 dark:text-white dark:hover:bg-gray-700 font-bold py-3 px-8 rounded-full transition-all transform hover:scale-105 focus:outline-none focus:ring-2 focus:ring-white focus:ring-opacity-50"
        >
          立即报名参加
        </a>
      </div>
    </section>

    <!-- Main Content -->
    <main class="container mx-auto px-4 py-8 space-y-12">
      <!-- Event Info Section -->
      <section
        id="event-info"
        class="event-info p-6 rounded-lg shadow-md bg-white dark:bg-gray-800"
      >
        <h2 class="text-2xl font-bold mb-4 text-blue-600 flex items-center">
          <div class="i-ri-information-line mr-2"></div>
          活动细则
        </h2>

        <div class="prose prose-gray dark:prose-invert max-w-none">
          <section>
            <h3>活动目的</h3>
            <p>
              依托通义灵码（阿里云智能编码助手）的技术能力，组织学生开展应用开发实践。
            </p>
            <ul>
              <li>面向计算机专业学生，促进理论知识向工程能力的转化</li>
              <li>赋能非计算机专业学生，降低创意实现的技术门槛</li>
              <li>
                通过本次活动，构建跨学科协作场景，提升校园技术创新氛围
              </li>
              <li>
                引导学生掌握AI工具的核心应用方法，培养适应智能化开发趋势的复合型人才
              </li>
            </ul>
          </section>

          <section>
            <h3>面向人群</h3>
            <ul>
              <li>
                核心参赛对象：大连理工大学全日制在校本科生（含大一至大四年级）
              </li>
              <li>跨专业组队要求：每队需含至少1名非计算机专业学生</li>
              <li>
                校外邀请机制：开放兄弟院校学生组队友情参与（颁发《友情参与证书》，不参与评奖）
              </li>
            </ul>
          </section>

          <section>
            <h3>团队构成规则</h3>
            <ul>
              <li>每队严格限定1-3人，需指定1名队长作为联系人</li>
              <li>鼓励计算机专业+非计算机专业组合（如软件工程+设计/机械等）</li>
              <li>
                跨专业队伍在评分中额外加1分创新性分值（需在报名表中注明专业构成）
              </li>
            </ul>
          </section>

          <section>
            <h3>比赛形式</h3>
            <ul>
              <li>赛事组委会将公布5个指定主题</li>
              <li>参赛队伍需基于AI IDE开发工具（通义灵码）进行项目开发</li>
              <li>项目形态可包括但不限于网站、移动应用（App）、桌面应用程序等</li>
            </ul>
          </section>
        </div>
      </section>

      <!-- Schedule Section -->
      <section
        id="schedule"
        class="schedule p-6 rounded-lg shadow-md bg-white dark:bg-gray-800"
      >
        <h2 class="text-2xl font-bold mb-4 text-blue-600 flex items-center">
          <div class="i-ri-calendar-line mr-2"></div>
          赛程安排
        </h2>

        <div class="overflow-x-auto">
          <table class="w-full border-collapse">
            <thead>
              <tr class="bg-gray-100 dark:bg-gray-700">
                <th class="border p-3 text-left">时间段</th>
                <th class="border p-3 text-left">关键任务</th>
                <th class="border p-3 text-left">执行细则</th>
              </tr>
            </thead>
            <tbody>
              <tr
                v-for="(item, index) in scheduleItems"
                :key="index"
                class="hover:bg-gray-50 dark:hover:bg-gray-600"
              >
                <td class="border p-3">{{ item.timeFrame }}</td>
                <td class="border p-3">{{ item.task }}</td>
                <td class="border p-3">{{ item.details }}</td>
              </tr>
            </tbody>
          </table>
        </div>
      </section>

      <!-- Awards Section -->
      <section
        id="awards"
        class="awards p-6 rounded-lg shadow-md bg-white dark:bg-gray-800"
      >
        <h2 class="text-2xl font-bold mb-4 text-blue-600 flex items-center">
          <div class="i-ri-trophy-line mr-2"></div>
          奖项设置与比例
        </h2>

        <div class="overflow-x-auto">
          <table class="w-full border-collapse">
            <thead>
              <tr class="bg-gray-100 dark:bg-gray-700">
                <th class="border p-3 text-left">奖项类型</th>
                <th class="border p-3 text-left">方案奖品组成</th>
              </tr>
            </thead>
            <tbody>
              <tr
                v-for="(award, index) in awardsList"
                :key="index"
                class="hover:bg-gray-50 dark:hover:bg-gray-600"
              >
                <td class="border p-3">{{ award.name }}</td>
                <td class="border p-3">{{ award.description }}</td>
              </tr>
            </tbody>
          </table>
        </div>
      </section>

      <!-- Register Section -->
      <section
        id="register"
        class="p-6 rounded-lg shadow-md bg-white dark:bg-gray-800"
      >
        <h2 class="text-2xl font-bold mb-4 text-blue-600 flex items-center">
          <div class="i-ri-edit-line mr-2"></div>
          报名须知
        </h2>

        <p class="mb-4">所有参赛队伍的队长需通过赛事官方网站完成团队报名。</p>

        <ol class="list-decimal pl-5 space-y-2 mb-6">
          <li>每队需指定1名队长作为联系人</li>
          <li>团队成员必须为1-3人</li>
          <li>跨专业队伍请在报名表中注明专业构成</li>
          <li>需提供每位参赛者的通义灵码账号用于验证</li>
        </ol>

        <div class="bg-blue-50 dark:bg-blue-900/30 p-4 rounded-lg mb-6">
          <h3 class="font-semibold text-lg mb-2 flex items-center">
            <div class="i-ri-lightbulb-line mr-2"></div>
            温馨提示
          </h3>
          <p>建议尽早报名以便获得更多赛事资源和支持！</p>
        </div>

        <button
          class="bg-blue-600 hover:bg-blue-700 text-white font-bold py-2 px-6 rounded-lg transition-colors focus:outline-none focus:ring-2 focus:ring-blue-500 focus:ring-opacity-50 flex items-center justify-center"
        >
          <div class="i-ri-arrow-right-circle-line mr-2"></div>
          前往报名页面
        </button>
      </section>
    </main>

    <!-- Footer -->
    <footer class="bg-white dark:bg-gray-800 shadow-inner py-8">
      <div class="container mx-auto px-4">
        <div class="flex flex-col md:flex-row justify-between items-center">
          <div class="mb-4 md:mb-0">
            <h3 class="font-bold text-lg">灵码杯赛事组</h3>
            <div class="flex items-center space-x-2">
              <span class="text-sm text-gray-500 dark:text-gray-400">技术支持：</span>
              <div class="flex items-center space-x-2">
                <img src="/tic.png" class="h-6" alt="TIC" />
                <img src="/naosi.svg" class="h-6" alt="脑丝" />
                <img src="/lingma.png" class="h-6" alt="通义灵码" />
              </div>
            </div>
          </div>
        </div>

        <div
          class="mt-6 pt-6 border-t border-gray-200 dark:border-gray-700 text-center text-gray-500 dark:text-gray-400"
        >
          <p>© 2025 灵码杯赛事组</p>
        </div>
      </div>
    </footer>
  </div>
</template>

<script setup>
import { ref } from "vue";

const scheduleItems = ref([
  {
    timeFrame: "06月25日 - 07月31日",
    task: "宣传预热期",
    details: "于各宣传平台（官⽅公众号、活动社群、友好院校开源社团等）发布赛事信息，启动参赛招募工作。",
  },
  {
    timeFrame: "07月04日 晚七点",
    task: "技术分享会",
    details: "邀请高年级学生代表分享通义灵码使用经验；由通义灵码技术团队进行产品功能教学与实践指导。",
  },
  {
    timeFrame: "07月15日 - 08月10日",
    task: "报名阶段",
    details: "正式放出赛事官网，开通线上报名通道（需完整填报团队信息，系统同步分配队伍编号）。报名通道将于08月10日24:00准时关闭。",
  },
  {
    timeFrame: "08月11日",
    task: "赛事正式启动",
    details: "比赛于08月11日00:00正式开始，同步发布全部5道赛题，并开启项目成果提交通道。",
  },
  {
    timeFrame: "08月20日",
    task: "提交截止",
    details: "项目成果提交通道于当日24:00关闭，逾期提交无效。",
  },
  {
    timeFrame: "08月21日 - 08月31日",
    task: "评审阶段",
    details: "评委组依据评审标准对所有有效提交项目进行评分。",
  },
  {
    timeFrame: "09月01日",
    task: "初评结果公示",
    details: "公布三等奖获奖名单及晋级路演环节（项目展示）的团队名单。同时公示三等奖及未晋级团队在评审阶段的得分明细。",
  },
  {
    timeFrame: "09月27日",
    task: "路演与终评颁奖",
    details: "上午9:00开始路演环节：各晋级团队队长现场抽签决定路演顺序。现场观众（线下到场）每人持有5票投票权（每票计5分）。路演结束后，即时将观众投票得分与评审阶段得分相加，依据总分排序并当场公布一等奖、二等奖获奖团队，颁发奖品。",
  },
]);

const awardsList = ref([
  {
    name: "一等奖（5%队伍）",
    description: "键盘迈从G87/人（价值:288/份）",
  },
  {
    name: "二等奖（15%队伍）",
    description: "罗技G102/人（价值:88/份）",
  },
  {
    name: "三等奖（30%队伍）",
    description: "灵码周边/人（棒球帽、手提袋、衬衫、鼠标垫随机发放）",
  },
  {
    name: "最佳创意奖（创新性评分最高的队伍）",
    description: "泰坦军团29.5英寸200hz曲面带鱼屏/队（价值:958）",
  },
  {
    name: "最佳设计奖（完成度评分最高的队伍）",
    description: "泰坦军团29.5英寸200hz曲面带鱼屏/队（价值:958）",
  },
  {
    name: "最佳新人奖（新生中排名前三的队伍）",
    description: "键盘迈从G87/队（价值:288/份）",
  },
]);
</script>