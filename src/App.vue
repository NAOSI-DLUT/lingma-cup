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
            href="#faq"
            class="text-blue-600 hover:text-blue-700 transition-colors flex items-center"
          >
            <div class="i-ri-question-line mr-1"></div>
            常见问题
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
                核心参赛对象：大连理工大学全日制在校学生（含大一至大四年级、全体研究生）
              </li>
              <li>含至少1名非计算机专业学生的队伍被认定为跨专业队伍（促进学科交叉创新，非强制要求）</li>
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
              <li>参赛队伍需基于且只能基于AI IDE开发工具（通义灵码）进行项目开发，允许部分手写代码</li>
              <li>项目形态可包括但不限于网站、移动应用（App）、桌面应用程序等</li>
            </ul>
          </section>

          <section>
            <h3>提交要求</h3>
            <p>开发周期结束后，各队需提交项目托管于<strong>GitHub或Gitee平台</strong>的代码仓库链接。</p>
            <p><strong>仓库内容必须包含：</strong></p>
            <ol>
              <li>
                <strong>项目说明文档（README.md）</strong>：清晰阐述项目创意、实现功能、运行/部署指南。若项目包含可执行成果（如部署的网站链接、可执行文件、安装包等），须在文档中明确说明访问方式或获取途径，可执行文件应发布至仓库的Release区域。
              </li>
              <li>
                <strong>完整源代码</strong>：提供可实际运行的项目源代码。项目能否成功运行将对最终评分产生显著影响。
              </li>
              <li>
                <strong>项目开发流程说明（chat.md）</strong>：清晰描述vibe coding流程，需提供用户输入的完整Prompt序列（包括用于引导AI IDE进行Bug修复的提示词）。
              </li>
            </ol>
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

      <!-- FAQ Section -->
      <section
        id="faq"
        class="p-6 rounded-lg shadow-md bg-white dark:bg-gray-800"
      >
        <h2 class="text-2xl font-bold mb-4 text-blue-600 flex items-center">
          <div class="i-ri-question-line mr-2"></div>
          常见问题
        </h2>

        <div class="space-y-4">
          <div
            v-for="(faq, index) in faqList"
            :key="index"
            class="border border-gray-200 dark:border-gray-600 rounded-lg"
          >
            <button
              @click="faq.isOpen = !faq.isOpen"
              class="w-full p-4 text-left flex justify-between items-center hover:bg-gray-50 dark:hover:bg-gray-700 transition-colors focus:outline-none focus:ring-2 focus:ring-blue-500 focus:ring-opacity-50 rounded-lg"
            >
              <span class="font-medium">{{ faq.question }}</span>
              <div
                :class="[
                  'transition-transform duration-200',
                  faq.isOpen ? 'rotate-180' : 'rotate-0'
                ]"
                class="i-ri-arrow-down-s-line text-xl"
              ></div>
            </button>
            <div
              v-show="faq.isOpen"
              class="px-4 pb-4 text-gray-700 dark:text-gray-300 faq-content"
            >
              <p v-html="faq.answer"></p>
            </div>
          </div>
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
          <p class="mb-3">建议尽早报名以便获得更多赛事资源和支持！</p>
          <div class="flex items-center space-x-2 text-sm">
            <div class="i-ri-qq-line text-blue-600 dark:text-blue-400"></div>
            <span class="font-medium">赛事交流群：</span>
            <span class="font-mono bg-white dark:bg-gray-700 px-2 py-1 rounded border">1040994124</span>
          </div>
        </div>

        <button
          @click="handleRegistration"
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

    <!-- 自定义弹窗 -->
    <div
      v-if="showModal"
      class="fixed inset-0 bg-black bg-opacity-50 flex items-center justify-center z-50 modal-overlay"
      @click="closeModal"
    >
      <div
        class="bg-white dark:bg-gray-800 rounded-lg shadow-xl max-w-md mx-4 w-full modal-content"
        @click.stop
      >
        <div class="p-6">
          <!-- 标题 -->
          <div class="flex items-center mb-4">
            <div
              :class="modalData.type === 'warning' ? 'i-ri-time-line' : 'i-ri-check-circle-line'"
              class="text-2xl mr-3"
              :style="{ color: modalData.type === 'warning' ? '#f59e0b' : '#10b981' }"
            ></div>
            <h3 class="text-lg font-semibold text-gray-900 dark:text-white">
              {{ modalData.title }}
            </h3>
          </div>

          <!-- 内容 -->
          <div class="mb-6 text-gray-700 dark:text-gray-300">
            <p class="mb-2">{{ modalData.message }}</p>
            <div
              v-if="modalData.countdownText"
              class="bg-blue-50 dark:bg-blue-900/30 p-3 rounded-lg"
            >
              <p class="text-sm font-medium text-blue-800 dark:text-blue-200">
                {{ modalData.countdownText }}
              </p>
            </div>
            <div
              v-if="modalData.tip"
              class="mt-3 p-3 bg-gray-50 dark:bg-gray-700 rounded-lg"
            >
              <p class="text-sm text-gray-600 dark:text-gray-400">
                💡 {{ modalData.tip }}
              </p>
            </div>
          </div>

                     <!-- 按钮 -->
           <div class="flex justify-end">
             <button
               @click="closeModal"
               class="px-4 py-2 bg-blue-600 text-white rounded-lg hover:bg-blue-700 transition-colors focus:outline-none focus:ring-2 focus:ring-blue-500"
             >
               我知道了
             </button>
           </div>
        </div>
      </div>
    </div>
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

const faqList = ref([
  {
    question: "哪些学生有参赛和评奖资格？",
    answer: "大连理工大学主校区、开发区校区、盘锦校区的<strong>本科生、研究生</strong>均有评奖资格。欢迎各校区的同学踊跃参与！",
    isOpen: false,
  },
  {
    question: "什么是跨专业组队？有什么具体要求？",
    answer: "跨专业组队的具体要求为：队内至少需要有<strong>两个不同学院</strong>的同学。需要注意的是，软件学院和国际信息与软件学院属于同一个学院。跨专业队伍可以获得额外的创新性加分！",
    isOpen: false,
  },
  {
    question: "队伍人数有什么限制？单人参赛有什么政策？",
    answer: "队伍人数上限为<strong>3人</strong>，可以1-3人自由组队。<strong>单人队伍将得到部分优惠政策</strong>。如果你暂时没有队友，欢迎在群内捞人组队！",
    isOpen: false,
  },
  {
    question: "技术讲座的回放地址在哪？后续还会有vibe coding相关的知识分享吗？",
    answer: "回放在：<a href='https://meeting.tencent.com/crm/N14kjJn3f0' target='_blank' rel='noopener noreferrer'>https://meeting.tencent.com/crm/N14kjJn3f0</a> ，后续<strong>还会有相关的分享</strong>，例如博客等等形式",
    isOpen: false,
  },
  {
    question: "路演在哪里举行？其他校区的学生怎么参加？",
    answer: "路演地点位于<strong>开发区校区</strong>。开发区校区的同学必须参加线下路演，其他校区（主校区、盘锦校区）的同学可以<strong>申请线上参加路演</strong>。",
    isOpen: false,
  },
  {
    question: "外校学生可以参加路演吗？",
    answer: "可以！外校队伍初赛排名的<strong>前20%</strong>可以申请参与线上路演。虽然外校队伍不参与正式评奖，但这是一个很好的交流学习机会。",
    isOpen: false,
  },
  {
    question: "在哪里可以找到详细的赛程安排和规则？",
    answer: "具体赛程安排请查看<strong>群文件细则</strong>，里面有完整的时间安排和详细规定。有任何问题都可以随时在群中交流或者私信赛事组成员！",
    isOpen: false,
  },
  {
    question: "如何加入赛事交流群？群号是多少？",
    answer: "QQ赛事交流群号：<strong>1040994124</strong>。群内可以寻找队友、获取最新资讯、技术交流答疑。有任何问题都可以在群中咨询赛事组成员！",
    isOpen: false,
  },
  {
    question: "如何寻找队友？有什么建议？",
    answer: "想跨专业组队的同学多在群里捞人！我们的活动交流群是寻找队友的最佳平台。也欢迎大家转发推广本赛事，让更多优秀的同学加入进来！",
    isOpen: false,
  },
]);

// 模态框状态
const showModal = ref(false);
const modalData = ref({
  type: 'warning', // 'warning' | 'success'
  title: '',
  message: '',
  countdownText: '',
  tip: ''
});

// 处理报名按钮点击
const handleRegistration = () => {
  const now = new Date();
  const registrationStartTime = new Date('2025-08-11T00:00:00');
  
  if (now < registrationStartTime) {
    // 计算剩余时间
    const timeDiff = registrationStartTime - now;
    const days = Math.floor(timeDiff / (1000 * 60 * 60 * 24));
    const hours = Math.floor((timeDiff % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
    const minutes = Math.floor((timeDiff % (1000 * 60 * 60)) / (1000 * 60));
    
    let timeRemaining = '';
    if (days > 0) {
      timeRemaining = `距离开始还有：${days}天${hours}小时${minutes}分钟`;
    } else if (hours > 0) {
      timeRemaining = `距离开始还有：${hours}小时${minutes}分钟`;
    } else {
      timeRemaining = `距离开始还有：${minutes}分钟`;
    }
    
    modalData.value = {
      type: 'warning',
      title: '报名暂未开始',
      message: '报名将于2025年8月11日0点正式开启',
      countdownText: timeRemaining,
      tip: '可先加入QQ群了解更多信息：1040994124'
    };
    showModal.value = true;
  } else {
    modalData.value = {
      type: 'success',
      title: '报名已开始',
      message: '请通过官方渠道进行报名',
      countdownText: '',
      tip: '详细信息请查看群文件或咨询群管理员'
    };
    showModal.value = true;
  }
};

// 关闭模态框
const closeModal = () => {
  showModal.value = false;
};
</script>

<style scoped>
.faq-content :deep(a) {
  color: #2563eb;
  text-decoration: none;
  padding: 2px 4px;
  border-radius: 4px;
  transition: all 0.2s ease-in-out;
  word-break: break-all;
}

.faq-content :deep(a:hover) {
  background-color: rgba(37, 99, 235, 0.1);
  box-shadow: 0 2px 8px rgba(37, 99, 235, 0.2);
}

/* 深色模式 */
:global(.dark) .faq-content :deep(a) {
  color: #60a5fa;
}

:global(.dark) .faq-content :deep(a:hover) {
  background-color: rgba(96, 165, 250, 0.1);
  box-shadow: 0 2px 8px rgba(96, 165, 250, 0.2);
}

/* 模态框动画 */
.modal-overlay {
  animation: fadeIn 0.3s ease-out;
}

.modal-content {
  animation: slideIn 0.3s ease-out;
}

@keyframes fadeIn {
  from {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
}

@keyframes slideIn {
  from {
    opacity: 0;
    transform: translateY(-20px);
  }
  to {
    opacity: 1;
    transform: translateY(0);
  }
}
</style>