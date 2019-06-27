<template>
  <q-page>
  <div class="row justify-center q-pa-sm">
    <div class="q-gutter-md">
      <q-carousel
        v-model="slide"
        transition-prev="scale"
        transition-next="scale"
        swipeable
        animated
        control-color="primary"
        navigation
        padding
        arrows
        flat
        style="width:650px; height: 400px; max-width: 100vw; max-height: 78vw"
        class="bg-white text-blue shadow-0 rounded-borders"
      >
      <q-carousel-slide name="topo" class="column no-wrap flex-center">
    <div class="q-mt-md text-center">
      <q-video style="width:500px; height: 300px; max-width: 75vw; max-height: 60vw"
        src="https://www.youtube.com/embed/6K5gy3RLcKc"
      ></q-video>
    </div>
  </q-carousel-slide>
  <q-carousel-slide name="topt" class="column no-wrap flex-center">
<div class="q-mt-md text-center">
  <q-video style="width:500px; height: 300px; max-width: 75vw; max-height: 60vw"
    src="https://www.youtube.com/embed/6PvGiXaAJpo"
  ></q-video>
</div>
</q-carousel-slide>
<q-carousel-slide name="topth" class="column no-wrap flex-center">
<div class="q-mt-md text-center">
<q-video style="width:500px; height: 300px; max-width: 75vw; max-height: 60vw"
  src="https://www.youtube.com/embed/dWFyRxZxE9A"
></q-video>
</div>
</q-carousel-slide>
  </q-carousel>
    </div>
    </div>
    <!-- Registered Channels with Latest Videos -->
    <div class="row justify-center">
      <div class="q-ma-md">
        <div class="q-ma-md" align="center">
          <q-avatar>
    <img src="https://yt3.ggpht.com/a/AGF-l7-sSYXoJQLN450mADMxMcK5vp1h824hq7dvTw=s88-mo-c-c0xffffffff-rj-k-no">
  </q-avatar>
        </div>
      <q-card style="width: 100%;
        max-width: 300px">
      <q-video
        src="https://www.youtube.com/embed/pTl42COCNaM"
      ></q-video>
         <q-card-section>
           <div class="text-h6">Corridor Crew</div>
           <q-item-label class="text-subtitle1" lines="1">VFX Artists React to Bad & Great CGi 4</q-item-label>
         </q-card-section>

         <q-card-section class="bg-primary">
            <!-- Hovering over it show full desc in tool tip -->
            <q-item-label caption class="text-bold text-white" lines="2">CONSIDER SUBSCRIBING ► http://bit.ly/Subscribe_Corridor_Crew
Watch This Show From The Beginning ► https://www.youtube.com/watch?v=kd8Ni.
        </q-item-label>
         </q-card-section>
       </q-card>
      </div>
      <div class="q-ma-md">
        <div class="q-ma-md" align="center">
          <q-avatar>
    <img src="https://yt3.ggpht.com/a/AGF-l7_bXISJmlqGf3NVpGPsunLN1-vNAPBNohat6A=s88-mo-c-c0xffffffff-rj-k-no">
  </q-avatar>
        </div>
      <q-card style="width: 100%;
        max-width: 300px">
      <q-video
        src="https://www.youtube.com/embed/amuemzOADlc"
      ></q-video>
         <q-card-section>
           <div class="text-h6">NoobFromUA</div>
           <q-item-label class="text-subtitle1" lines="1">EG vs GAMBIT - WINNERS LOSERS DECIDER - EPICENTER MAJOR 2019 DOTA 2</q-item-label>
         </q-card-section>

         <q-card-section class="bg-primary">
            <!-- Hovering over it show full desc in tool tip -->
            <q-item-label caption class="text-bold text-white" lines="2">Commentary by @DSwordfish & @Garethcasts
EG vs GAMBIT - WINNERS LOSERS DECIDER - EPICENTER MAJOR 2019 DOTA 2
        </q-item-label>
         </q-card-section>
       </q-card>
      </div>
      <div class="q-ma-md">
        <div class="q-ma-md" align="center">
          <q-avatar>
    <img src="https://yt3.ggpht.com/a/AGF-l79HcAixNh0ysI5QtPLvYk8ypt7gkGdgJZ2bpg=s88-mo-c-c0xffffffff-rj-k-no">
  </q-avatar>
        </div>
      <q-card style="width: 100%;
        max-width: 300px">
      <q-video
        src="https://www.youtube.com/embed/jrVwqQVCrLw"
      ></q-video>
         <q-card-section>
           <div class="text-h6">Bloomberg</div>
          <q-item-label class="text-subtitle1" lines="1">The Experts Teaching Self-Driving Cars How to Drive</q-item-label>
         </q-card-section>

         <q-card-section class="bg-primary">
            <!-- Hovering over it show full desc in tool tip -->
            <q-item-label caption class="text-bold text-white" lines="2">Autonomous cars are only as good as the human drivers they learn from — so the people who teach these systems how to drive need to be excellent drivers themselves. To get a look at what it takes to do this job, Bloomberg Technology’s Aki Ito recently joined two vehicle operators who work
        </q-item-label>
         </q-card-section>
       </q-card>
      </div>
    </div>
  </q-page>
</template>

<style>
</style>

<script>
export default {
  name: 'PageIndex',
  data () {
    return {
      slide: 'topo',
      channels: [],
      topChannels: []
    }
  }
}
</script>
