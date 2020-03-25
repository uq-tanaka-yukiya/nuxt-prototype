<template>
  <section>
    <p>火葬のみ行う２つの低価格プラン</p>
    <b-row>
      <b-col>
        <PlanCard
          image="https://placehold.jp/480x200.png"
          link="a"
          title="aaa"
        />
      </b-col>
      <b-col>
        <PlanCard
          image="https://placehold.jp/480x200.png"
          link="a"
          title="aaa"
        />
      </b-col>
    </b-row>
    <p>最期のお別れをゆっくり過ごせる 式を行う3つのプラン</p>
    <b-row>
      <b-col>
        <PlanCard
          image="https://placehold.jp/300x380.png"
          link="a"
          title="aaa"
        />
      </b-col>
      <b-col>
        <PlanCard
          image="https://placehold.jp/300x380.png"
          link="a"
          title="aaa"
        />
      </b-col>
      <b-col>
        <PlanCard
          image="https://placehold.jp/300x380.png"
          link="a"
          title="aaa"
        />
      </b-col>
    </b-row>
    <b-row>
      <b-col>
        火葬料金は別途お客様負担となります
      </b-col>
    </b-row>
  </section>
</template>

<script lang="ts">
import PlanCard from '../../molecules/plan/PlanCard'

export default {
  components: {
    PlanCard
  }
}
</script>
