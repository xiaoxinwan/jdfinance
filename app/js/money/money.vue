<template>
  <Panel :class="$style.panel" title="理财精选">
    <ul :class="$style.content">
      <li>
        <img src="//img12.360buyimg.com/jrpmobile/jfs/t3670/58/543125556/2606/a65096b9/580d80afN63b1085a.png?width=76&height=76" alt="">
        <div>
          <h4>月度理财</h4>
          <p>预期年化收益率4.50%</p>
        </div>
        <em>去赚钱 ></em>
      </li>
      <li>
        <img src="//img12.360buyimg.com/jrpmobile/jfs/t3679/44/511862277/2728/c1c6b2bf/580d8189N6b6f8052.png?width=76&height=76" alt="">
        <div>
          <h4>季度理财</h4>
          <p>历史年化回报率5.50%</p>
        </div>
        <em>去赚钱 ></em>
      </li>
      <li>
        <img src="//img12.360buyimg.com/jrpmobile/jfs/t3331/69/580199498/3074/d5bb21c5/580d7f6cN7f35e596.png?width=76&height=76" alt="">
        <div>
          <h4>一年理财</h4>
          <p>历史年化回报率5.80%</p>
        </div>
        <em>去赚钱 ></em>
      </li>
    </ul>
  </Panel>
</template>

<script>
import Panel from '../core/panel.vue';
  export default {
    components: {Panel}
  }
</script>

<style lang="scss" module>
  @import '../../css/element.scss';
  .panel{
    @include panel;
    .content{
      @include flex;
      li{
        @include flex(row);
        height: 140px;
        box-sizing: border-box;
        align-items: center;
        img{
          width: 88px;
          height: 88px;
          display: inline-block;
          margin: 0 32px;
        }
        >div{
          font-size: 32px;
          line-height: 1.8;
          color: #333;
          width: 344px;
          p{
            color: #ff3232;
            font-size: 24px;
            line-height: 1.1;
            white-space: nowrap;
            text-overflow: ellipsis;
            overflow: hidden;
          }
        }
        >em{
          color: #ff801a;
          font-size: 28px;
        }
      }
    }
  }
</style>