<template>
  <el-container class="home-container">
    <el-container class="home-main-container">
      <el-container class="home-main-row">
        <el-container class="home-brief">
          <el-container class="home-brief-inner">
            <img class="home-main-logo" src="@/assets/images/orglogo.jpg" />
            <label class="home-brief-text">
              “碳益未来”团队背靠南京大学，不断优化和完善矿化封存系统，确保其在实际应用中的高效稳定，拥有多项国家专利，掌握核心技术；并且通过与钢铁企业合作的方式，共享技术和市场资源，共同推动CCUS技术的商业化应用。
            </label>
          </el-container>
        </el-container>
        <el-container class="home-content">
          <el-container class="home-content-inner">
            <label class="main-content-text">
              &emsp;&emsp;在全球气候变化形势日益严峻的今天，经济和环境的可持续发展，成为全人类共同面临的重大课题。为了全人类的生息与福祉，中国政府向世界庄严宣告了2030年实现“碳达峰”，2060年实现“碳中和”的伟大愿景。为此，“碳益未来”应运而生于中国南京，推出具有突破性的创新技术，解决以钢铁冶炼为代表的工业生产中，长期存在的高碳排放问题。针对钢铁行业这一典型高排放领域，“碳益未来”提供了一套完整的二氧化碳捕集与封存（CCUS）解决方案，利用钢铁生产中的冶炼废渣作为二氧化碳矿化封存的媒介，通过先进的pH-swing技术和ALKALoop二氧化碳高值矿化技术，从工业废气中高效脱除二氧化碳，以极低的能耗将之转化为高附加值、易于利用的副产品——轻质碳酸钙，一举两得地解决了钢铁冶炼的废气和废渣处理两大难题，另辟蹊径，变废为宝，在实现节能减排目标的同时亦创造可观的经济效益。
            </label>
            <label class="main-content-text">
              &emsp;&emsp;捕碳增益，共赴未来。“碳益未来”在发展的历程中，将永远秉持“科技引领、创新驱动”的初心使命，为实现碳达峰和碳中和的目标积极献力，心系天下苍生，与全中国乃至全世界，共建低碳、绿色、可持续的美好明天。
            </label>
          </el-container>
        </el-container>
      </el-container>
      <el-container class="home-logos">
        <el-container class="home-logos-inner">
          <el-row>
            <label class="home-logo-title">
              <strong>合作伙伴</strong>
            </label>
          </el-row>
          <el-row style="background-color: #fff;">
            <a href="http://www.xusteel.cn" class="home-logo-link" target="_blank">
              <img class="home-logo" src="@/assets/images/org1.png" />
            </a>
            <a href="https://inco.cscec.com" class="home-logo-link" target="_blank">
              <img class="home-logo" src="@/assets/images/org2.png" />
            </a>
            <a href="http://cpecc.cnpc.com.cn" class="home-logo-link" target="_blank">
              <img class="home-logo" src="@/assets/images/org3.png" />
            </a>
            <a href="http://www.jsjajt.com" class="home-logo-link" target="_blank">
              <img class="home-logo" src="@/assets/images/org4.png" />
            </a>
            <a href="about:blank" class="home-logo-link" target="_blank">
              <img class="home-logo" src="@/assets/images/org5.png" />
            </a>
          </el-row>
        </el-container>
      </el-container>
    </el-container>
    <el-footer class="home-footer">
      <label class="home-footer-text">联系我们： Email: zhaoliang@nju.edu.cn</label>
    </el-footer>
  </el-container>
</template>

<style scoped>
.home-main-row {
  padding: 0;
  margin: 0;
  display: inline-flex;
  flex-direction: row;
  width: calc(100vw - 20px);
}

.home-brief {
  width: 33vw;
  padding: 15px;
}

.home-brief-inner {
  display: inline-flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  padding: 15px;
  padding-left: 25px;
  background-color: rgba(255, 255, 255, 0.8);
  border-radius: 15px;
}

.home-main-logo {
  width: 25vw;
  height: auto;
  margin-bottom: 35px;
}

.home-brief-text {
  font-size: 32px;
}

.home-content {
  display: inline-flex;
  flex-direction: column;
  padding: 15px;
  width: calc(67vw - 20px);
}

.home-content-inner {
  display: inline-flex;
  flex-direction: column;
  padding: 15px;
  background-color: rgba(255, 255, 255, 0.8);
  border-radius: 15px;
  justify-content: center;
  align-items: center;
}

.main-content-title {
  font-size: 38px;
}

.main-content-text {
  font-size: 25px;
  margin: 5px 30px;
}

.home-container {
  height: 100vh;
  width: 100vw;
  background-image: url("@/assets/images/display.jpg");
  background-size: cover;
}

.home-header-logo {
  height: 100%;
  width: auto;
}

.home-main-container {
  height: calc(100vh - 120px);
  flex-direction: column;
  padding: 10px;
}

.home-logos {
  padding: 15px;
  padding-top: 10px;
}

.home-logos-inner {
  display: flex;
  flex-direction: column;
  padding: 15px;
  padding-top: 10px;
  border-radius: 15px;
  background-color: rgba(255, 255, 255, 0.8);
  justify-content: center;
  align-items: center;
}

.home-logo-title {
  font-size: 36px;
  margin-bottom: 15px;
}

.home-logo-link {
  margin: 0 auto;
}

.home-logo {
  height: 96px;
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
