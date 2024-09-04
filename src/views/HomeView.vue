<template>
  <el-container class="home-container">
    <el-header class="home-header">
      <img class="home-header-logo" src="@/assets/images/orglogo.jpg" />
      <label class="home-header-contact">联系我们： Email: zhaoliang@nju.edu.cn</label>
    </el-header>
    <el-container class="home-main-container">
      <el-aside class="home-main">
        <label class="home-label-title">
          <strong>企业介绍：</strong>
        </label>
        <label class="home-label-text">
          &emsp;&emsp;在全球气候变化形势日益严峻的今天，经济和环境的可持续发展，成为全人类共同面临的重大课题。为了全人类的生息与福祉，中国政府向世界庄严宣告了2030年实现“碳达峰”，2060年实现“碳中和”的伟大愿景。为此，“碳益未来”应运而生于中国南京，推出具有突破性的创新技术，解决以钢铁冶炼为代表的工业生产中，长期存在的高碳排放问题。针对钢铁行业这一典型高排放领域，“碳益未来”提供了一套完整的二氧化碳捕集与封存（CCUS）解决方案，利用钢铁生产中的冶炼废渣作为二氧化碳矿化封存的媒介，通过先进的pH-swing技术和ALKALoop二氧化碳高值矿化技术，从工业废气中高效脱除二氧化碳，以极低的能耗将之转化为高附加值、易于利用的副产品——轻质碳酸钙，一举两得地解决了钢铁冶炼的废气和废渣处理两大难题，另辟蹊径，变废为宝，在实现节能减排目标的同时亦创造可观的经济效益。
        </label>
        <label class="home-label-text">
          &emsp;&emsp;“碳益未来”团队背靠南京大学，不断优化和完善矿化封存系统，确保其在实际应用中的高效稳定，拥有多项国家专利，掌握核心技术；并且通过与钢铁企业合作的方式，共享技术和市场资源，共同推动CCUS技术的商业化应用。
        </label>
        <label class="home-label-text">
          &emsp;&emsp;捕碳增益，共赴未来。“碳益未来”在发展的历程中，将永远秉持“科技引领、创新驱动”的初心使命，为实现碳达峰和碳中和的目标积极献力，心系天下苍生，与全中国乃至全世界，共建低碳、绿色、可持续的美好明天。
        </label>
      </el-aside>
      <el-main class="home-aside">
        <label class="home-label-title">
          <strong>我们的合作伙伴：</strong>
        </label>
        <a href="http://www.xusteel.cn" class="home-aside-link" target="_blank">
          <img class="home-aside-logo" src="@/assets/images/org1.png" />
        </a>
        <a href="https://inco.cscec.com" class="home-aside-link" target="_blank">
          <img class="home-aside-logo" src="@/assets/images/org2.png" />
        </a>
        <a href="http://cpecc.cnpc.com.cn" class="home-aside-link" target="_blank">
          <img class="home-aside-logo" src="@/assets/images/org3.png" />
        </a>
        <a href="http://www.jsjajt.com" class="home-aside-link" target="_blank">
          <img class="home-aside-logo" src="@/assets/images/org4.png" />
        </a>
        <a href="about:blank" class="home-aside-link" target="_blank">
          <img class="home-aside-logo" src="@/assets/images/org5.png" />
        </a>
      </el-main>
    </el-container>
    <el-footer class="home-footer">
      <label class="home-footer-text">COPYRIGHT © NANJING UNIVERSITY ALL RIGHTS RESERVED</label>
    </el-footer>
  </el-container>
</template>

<style scoped>
.home-container {
  height: 100vh;
  width: 100vw;
}

.home-header {
  border-bottom: 1px solid rgba(0, 0, 0, 0.5);
  display: inline-flex;
}

.home-header-contact {
  margin: auto;
  font-size: large;
  margin-right: 15px;
}

.home-header-logo {
  height: 100%;
  width: auto;
}

.home-main-container {
  height: calc(100vh - 120px);
  flex-direction: row;
}

.home-main {
  width: 55vw;
  padding: 0 3vw;
  border-right: 1px solid rgba(0, 0, 0, 0.8);
  height: calc(100vh - 120px);
  margin: 0;
  display: flex;
  flex-direction: column;
}

.home-label-title {
  font-size: xx-large;
  margin-top: 45px;
  margin-bottom: 10px;
}

.home-label-text {
  font-size: 22px;
  margin: 10px;
  padding: 0 25px;
}

.home-aside {
  height: calc(100vh - 120px);
  width: 35vw;
  padding: 0 3vw;
  display: flex;
  flex-direction: column;
}

.home-aside-link {
  margin: 15px auto;
}

.home-aside-logo {
  height: 100px;
  width: auto;
}

.home-footer {
  background-color: #6f106e;
  display: flex;
}

.home-footer-text {
  font-size: 20px;
  color: white;
  text-shadow: 0 0 12px white;
  margin: auto;
}
</style>
