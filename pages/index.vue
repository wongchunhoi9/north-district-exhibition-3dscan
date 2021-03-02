<template>
  <div>
    <b-container class="catalog-container" >
      <b-row>
        <b-col>
          <div>
            <h4>立體掃瞄</h4>
            <p>
              匆匆探訪了數個紮根北區的居民，我從旁觀察了他們人生之中很短很短的剎那。並帶走了幾件我認為可能反映到他們當下生活的一些東西。有的是他們珍而重之的用具，有的是他們的日常生產的東西，有的更可能是北區居民剛剛買到過的食物。這都是他們見慣見熟、不以為然的東西。這些物件全部都以「手信」的形式來到我這「外地人」手上。我把這些他們慷慨贈之的東西做了立體描掃，不為什麼保留不保留什麼獨特的歷史文化價值，只為提供另一個面向去仔細看看居民生活這小單位歷史。
            </p>
          </div>
        </b-col>
      </b-row>
    </b-container>

    <b-container>
      <b-row>
        <b-col>
          <nuxt-link to="farmerstickwithbutton">  <h2>demo on ipad display set 1 (please use tablet to open this link for demo</h2></nuxt-link>
          <nuxt-link to="pepperwithbutton">  <h2>demo on ipad display set 2 (please use tablet to open this link for demo</h2></nuxt-link>
        </b-col>
      </b-row>
    </b-container>


    <!-- 坪輋 財哥 (魚菜共生實驗農場負責人) -->
    <b-container class="session-container" >
      <h5>坪輋 財哥 (魚菜共生實驗農場負責人)</h5>
      
      <b-row  >
        <b-col md="6" >
            <NuxtLink to="/farmerstick">
              <div>
                <h4> 禾旱草擔挑</h4>
                    <iframe title="HoneyComb" width="100%" height="400px" src="https://sketchfab.com/models/474aaceb6ae249919f48112acf4fb2ce/embed">
                    </iframe>
                   
              </div> 
            </NuxtLink>
            <p> 他兒時有用到的一款工具，現在已很稀有的。是一支用花梨木製成的全手造擔挑，外型像雙頭矛，用作一次過搬運數扎禾旱草之用。      </p>
        </b-col>
        <b-col md="6">
            <NuxtLink to="/raddish">
              <div>
                <h4> 蘿蔔</h4>
                    <iframe title="HoneyComb" width="100%" height="400px" src="https://sketchfab.com/models/b35456dd949d463f92a1f7902b34d3f7/embed">
                    </iframe>
                   
              </div> 
            </NuxtLink>
            <p>
                跟財哥去看農田途中遇到同村的鄰居李太，她給了幾條木薯財哥，是剛剛在田收成的。探訪期間正值新年前夕，坪輋一帶的農田都有蘿蔔，這是我隨手在田拔的一條。
            </p>
            
        </b-col>
      </b-row>
    </b-container>

     <!-- 聯和墟 面包店店主  鍾先生 -->
    <b-container class="session-container">
      <h5>聯和墟 面包店店主  鍾先生</h5>
      <p> </p>
      <b-row >
        <b-col>
            <NuxtLink to="/chickenbread">
              <div>
                <h4> 雞牌包 </h4>
             
                    <iframe title="HoneyComb" width="100%" height="400px" src="https://sketchfab.com/models/7af970244a074be8ba4cbf79ef7e4e7d/embed?autospin=1&camera=0">
                    </iframe>
                   
              </div> 
            </NuxtLink>
          <p>鍾先生經營的面包店的招牌款式面包</p>   
        </b-col>
      </b-row>
    </b-container>

     <!-- 坪輋 強B哥 (採蜂人) -->
    <b-container class="session-container">
      <h5>坪輋 強B哥 (採蜂人)</h5>
      
      <b-row >
        <b-col>
            <NuxtLink to="/honeycomb">
              <div>
                <h4> 蜜蜂巢</h4>
                    <iframe title="HoneyComb" width="100%" height="400px" src="https://sketchfab.com/models/91604ec8cc6940e4be04e324c9c13582/embed?autospin=1&camera=0">
                    </iframe>
                   
              </div> 
            </NuxtLink>
            <p> 新鮮蜂巢- 還滲著蜜糖的新鮮小型蜂巢</p>
        </b-col>
      </b-row>
    </b-container>

   

    <!-- >馬屎埔 區家< -->
    <b-container class="session-container">
      <h5>馬屎埔 區家</h5>
      <p> - 平平無期，卻就是連我家住上水的姨媽也會特地騎單車去馬寶寶農場買的蔬果</p>
      <b-row >
        <b-col>
            <NuxtLink to="/pepper">
              <div>
                <h4> 虎牙椒</h4>
                  <iframe title="pepper" width="100%" height="400px"  src="https://sketchfab.com/models/248055229ebb41fcb4e5c7fa87ad944c/embed">
                  </iframe> 
              </div> 
            </NuxtLink>
        </b-col>
        <b-col>
            <NuxtLink to="/tomato">
              <div>
                <h4> 自家種蕃茄</h4>
                   <iframe title="Tomato" width="100%" height="400px"  src="https://sketchfab.com/models/93a095fce08b47f0980e41fc89023953/embed">
                  </iframe> 
              </div> 
            </NuxtLink>
        </b-col>
      </b-row>
      
    </b-container>

    
  </div>

  
</template>

<script>



</script>

<style>
.catalog-container {
  width: 100%;
  padding: 4%;
}

.session-container { 
  background-color: antiquewhite;
  padding: 2rem;
  border: black;
  border-style:solid;
}
</style>
