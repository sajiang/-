<template>
  <div id="app">
    <div class="set1">
      <img class="logo" style="width: 90px;height: 90px;" src="../static/img/logo.png">
      <div class="des">
        <div class="font42">开元棋牌-下载送365元</div>
        <div class="sub">
          <div>
            <div class="font28 grey mgt10">百人牛牛 抢庄牛牛 百家乐</div>
            <div>
              <img v-for="i in 5" class="star" src="./assets/star.png">
              <span class="font26 grey"> 3.6万人下载</span>
            </div>
          </div>
          <div class="download">
            <img src="./assets/download1.gif">
          </div>
        </div>
      </div>
    </div>
    <div class="set2">
      <img class="backg" src="./assets/backg.jpg">
      <div class="download">
        <img src="./assets/iosdl.png">
        <img src="../static/img/Androiddl.png">
      </div>
    </div>
    <div class="set3">
      <div class="center">
        <img class="separateLine" src="./assets/separateLine.png">
      </div>
      <div>
        <div class="features">
          <div class="featureLogo">
            <img class="featureLogo1" src="./assets/feature1.png">
          </div>
          <div>
            <div class="featureLogoSlogan">
              <img class="featureLogoSlogan1" src="./assets/slogan1.png">
            </div>
            <div class="desc">
              <div>多平台 多种棋牌玩法，万人在线参与，真人对战，真实有趣。</div>
            </div>
          </div>
        </div>
        <div class="features">
          <div class="featureLogo">
            <img class="featureLogo2" src="./assets/feature2.png">
          </div>
          <div>
            <div class="featureLogoSlogan">
              <img class="featureLogoSlogan2" src="./assets/slogan2.png">
            </div>
            <div class="desc">
              <div>晋级彩金、周彩金、月彩金，各种彩金免费送，特权享不停。</div>
            </div>
          </div>
        </div>
        <div class="features">
          <div class="featureLogo">
            <img class="featureLogo3" src="./assets/feature3.png">
          </div>
          <div>
            <div class="featureLogoSlogan">
              <img class="featureLogoSlogan3" src="./assets/slogan3.png">
            </div>
            <div class="desc">
              <div>账号特权福利永久保值，还可以自由买卖账号，享有原账号权益特权。</div>
            </div>
          </div>
        </div>
        <div class="features">
          <div class="featureLogo">
            <img class="featureLogo4" src="./assets/feature4.png">
          </div>
          <div>
            <div class="featureLogoSlogan">
              <img class="featureLogoSlogan4" src="./assets/slogan4.png">
            </div>
            <div class="desc">
              <div>一键分享，成为代理，零成本，高收益，轻松躺赢，豪车美女不是梦。</div>
            </div>
          </div>
        </div>
        <div class="features">
          <div class="featureLogo">
            <img class="featureLogo5" src="./assets/feature5.png">
          </div>
          <div>
            <div class="featureLogoSlogan">
              <img class="featureLogoSlogan5" src="./assets/slogan5.png">
            </div>
            <div class="desc">
              <div>不用利息，账号在手就能借钱，分期还款，解决您的燃眉之急。</div>
            </div>
          </div>
        </div>
        <div class="features borderNone">
          <div class="featureLogo">
            <img class="featureLogo6" src="./assets/feature6.png">
          </div>
          <div>
            <div class="featureLogoSlogan">
              <img class="featureLogoSlogan6" src="./assets/slogan6.png">
            </div>
            <div class="desc">
              <div>顶级安防系统，资金安全有保障，</div>
              <div>存取款火速到账！</div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="set4">
      <div class="center">
        <img class="separateLine" src="./assets/separateLine2.png">
      </div>
      <div class="center pdb10">
        <div class="otherGameCard">
          <img class="gamePic" src="./assets/game1.png">
          <div class="desc">
            <div>
              <img class="gamelogo" src="./assets/gamelogo1.png">
            </div>
            <div>
              <img class="download" src="./assets/download2.png">
            </div>
            <div class="font24 darkBlue">
              (8.6万人下载)
            </div>
          </div>
        </div>
      </div>
      <div class="center pdb10">
        <div class="otherGameCard">
          <img class="gamePic" src="./assets/game2.png">
          <div class="desc">
            <div>
              <img class="gamelogo" src="./assets/gamelogo2.png">
            </div>
            <div>
              <img class="download" src="./assets/download2.png">
            </div>
            <div class="font24 darkBlue">
              (5.9万人下载)
            </div>
          </div>
        </div>
      </div>
      <div class="center pdb10">
        <div class="otherGameCard">
          <img class="gamePic" src="./assets/game3.png">
          <div class="desc">
            <div>
              <img class="gamelogo" src="./assets/gamelogo3.png">
            </div>
            <div>
              <img class="download" src="./assets/download2.png">
            </div>
            <div class="font24 darkBlue">
              (8.6万人下载)
            </div>
          </div>
        </div>
      </div>
      <div class="center pdb10">
        <div class="otherGameCard block">
          <div class="flex">
            <div class="item">
              <div>
                <img class="gamelogo" src="./assets/gamelogo4.png">
              </div>
              <div>
                <img class="download" src="./assets/download2.png">
              </div>
              <div class="font24 darkBlue">
                (5.2万人下载)
              </div>
            </div>
            <div class="item">
              <div>
                <img class="gamelogo" src="./assets/gamelogo5.png">
              </div>
              <div>
                <img class="download" src="./assets/download2.png">
              </div>
              <div class="font24 darkBlue">
                (7.3万人下载)
              </div>
            </div>
            <div class="item">
              <div>
                <img class="gamelogo" src="./assets/gamelogo6.png">
              </div>
              <div>
                <img class="download" src="./assets/download2.png">
              </div>
              <div class="font24 darkBlue">
                (8.6万人下载)
              </div>
            </div>
          </div>
          <div class="center darkBlue font24 mgt10">还有更多游戏等您来挑战</div>
        </div>
      </div>
    </div>
    <div class="footer darkBlue">
      <div>
        <img class="logo" src="./assets/logo2.png">
        <span>开元棋牌</span>
      </div>
      <div class="font28 mgt10">
        COPYRIGHT © 2018 开元棋牌
      </div>
    </div>
  </div>
</template>

<script>

export default {
  name: 'App',
}
</script>

<style>
#app {
  background:linear-gradient( #2B2F35,#1F2326);
}
.mgt10{
  margin-top: 10px;
}
.pdb10{
  padding-bottom: 10px;
}
.center{
  text-align: center;
}
.grey{
  color: #999;
}
.darkBlue{
  color: #6C727C;
}
.block{
  display: inline-block !important;
  background-size: 100% 100% !important;
  padding:40px 0 0 0;
}
.font42{
  font-size: 42px;
}
.font28{
  font-size: 28px;
}
.font26{
  font-size: 26px;
}
.font24{
  font-size: 24px;
}
.set1{
  background-color: white;
  display: flex;
  & .logo{
    
  }
  & .des{
    flex: 1;
    margin-left: 10px;
    & .sub{
      display: flex;
      line-height: 1.7;
      & .star{
        width: 32px;
        height: 29px;
        margin-right: 5px;
      }
    }
    & .download{
      flex: 1;
      text-align: center;
      & img{
        width: 184px;
        height: 96px;
      }
      
    }
  }
  
}
.set2{
  position: relative;
  & .backg{
    width: 750px;
  }
  & .download{
    position:  absolute;
    bottom: 0;
    left: 50%;
    margin-left: -228px;
    & img{
      width: 456px;
      height: 127px;
      margin: 15px 0;
    }
  }
}
.set3{
  margin-top: 20px;
  & .separateLine{
    width: 658px;
    height: 33px;
    margin-bottom: 20px;
  }
  & .features{
    display: flex;
    height: 190px;
    align-items: center;
    margin: 0 50px;
    border-bottom: 1px solid #383C44;
    & .featureLogo{
      width: 180px;
      & .featureLogo1{
        width: 124px;height: 74px;
      }
      & .featureLogo2{
        width: 117px;height: 94px;
      }
      & .featureLogo3{
        width: 116px;height: 102px;
      }
      & .featureLogo4{
        width: 102px;height: 97px;
      }
      & .featureLogo5{
        width: 96px;height: 121px;
      }
      & .featureLogo6{
        width: 112px;height: 118px;
      }
    }
    & .featureLogoSlogan{
      & .featureLogoSlogan1{
        width: 297px;height: 35px;
      }
      & .featureLogoSlogan2{
        width: 394px;height: 43px;
      }
      & .featureLogoSlogan3{
        width: 442px;height: 36px;
      }
      & .featureLogoSlogan4{
        width: 297px;height: 35px;
      }
      & .featureLogoSlogan5{
        width: 142px;height: 35px;
      }
      & .featureLogoSlogan6{
        width: 253px;height: 35px;
      }
    }
    & .desc{
      margin-top: 10px;
      color: #6C727C;
      font-size: 24px;
      line-height: 1.5;
      width:450px;
    }
  }
  & .borderNone{
    border-bottom: none;
  }
}
.set4{
  margin-top: 20px;
  padding-bottom: 20px;
  & .separateLine{
    width: 658px;
    height: 33px;
    margin-bottom: 20px;
  }
  & .otherGameCard{
    background: url('../static/img/backBlock.png');
    width: 667px;
    height: 320px;
    background-size: cover;
    display: inline-flex;
    align-items: center;
    & .gamePic{
      width: 422px;
      height: 260px;
      margin-left: 35px;
    }
    & .desc{
      flex: 1;
      text-align: center;
    }
    & .gamelogo{
      width: 133px;
      height: 135px;
    }
    & .download{
      width: 154px;
      height: 47px;
    }
    & .flex{
      display: flex;
      flex: 1;
      justify-content:space-around;
      & .item{
        flex: 1
      }
      & .item:not(:first-child){
        border-left: 2px solid #282F36;
      }
    }
  }
}
.footer{
  padding: 30px;
  text-align: center;
  background-color: #272E36;
  font-size: 34px;
  & .logo{
    width: 45px;
    height: 35px;
  }
}
</style>
