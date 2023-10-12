<template>
  <DropZone ncBgType="bgColor" backgroundImage="" id="dcc8654f-40e9-4a19-9d4e-c4456ec2ab9e"
    v-bind:style="{'width':'100%','height':'auto'}">
    <AdvanceDatatable v-bind:items="bindSource('functions.getPriceElements.data.priceElements')"
      v-bind:fields="[{'label':'Id','key':'id','sortable':true,'searchable':true,'class':'','thStyle':{'width':'100px'}},{'label':'Type','key':'type','sortable':true,'searchable':true,'class':''},{'label':'Name','key':'name','sortable':true,'searchable':true,'class':''},{'label':'Amount','key':'amount','sortable':true,'searchable':true,'class':''},{'label':'Quantity','key':'quantity','sortable':true,'searchable':true,'class':''},{'label':'Tax','key':'tax','sortable':true,'searchable':true,'class':''},{'label':'CurrencyCode','key':'currencyCode','sortable':true,'searchable':true,'class':''},{'label':'SortOrder','key':'sortOrder','sortable':true,'searchable':true,'class':''},{'label':'PriceIncludedInId','key':'priceIncludedInId','sortable':true,'searchable':true,'class':'d-none'}]"
      v-bind:isBusy="false" v-bind:isFixed="true" v-bind:isHover="false"
      mapping="functions.getPriceElements.data.priceElements" v-bind:perPage="5"
      emptyTxt="This datatable is currently empty, but you can customize it with your information."
      v-bind:isStriped="true" hoverColor="#EDEDED" selectMode="multi" v-bind:allowExport="true" borderColor="#cdcdcd"
      emptyHeader="Header" v-bind:isFootClone="false" v-bind:outerBorder="true" downloadType="CSV"
      v-bind:isResponsive="true" v-bind:isSelectable="true" v-bind:hasPagination="true" v-bind:searchControl="true"
      v-bind:showTotalRows="true"
      emptyFilterTxt="Please consider using different keywords or filters and try your search again."
      v-bind:filterDebounce="0" v-bind:smallSelection="false" textDecoration="none" headerTextColor="#606060"
      v-bind:isFooterSorting="true" selectedRowColor="#E3EEFB" borderAffectedArea="all" v-bind:defaultSelectedRow="0"
      v-bind:refreshButtonControl="true" v-bind:tableBodyOuterBorder="true" headerBackgroundColor="#FFFFFF"
      cellVerticalBorderColor="#cdcdcd" v-bind:tableCellVerticalBorder="true" cellHorizontalBorderColor="#cdcdcd"
      tableBodyOuterBorderColor="#cdcdcd" v-bind:tableCellHorizontalBorder="true" position="relative"
      v-bind:snapX="false" v-bind:snapY="false" id="53821db8-c85f-4daa-b988-d1b7dcba64d2"
      v-bind:style="{'color':'#606060','width':'100%','height':'100%','minWidth':'350px','fontStyle':'normal','minHeight':'150px','textAlign':'left','wordBreak':'keep-all','background':'#FFFFFF','fontFamily':'Inter','fontWeight':400,'textIndent':'0px','visibility':'visible','whiteSpace':'nowrap','wordSpacing':'0px','letterSpacing':'0px','textTransform':'none','zIndex':2}"/>
    <WDangerButton tag="button" href="" v-bind:pill="false" size="md" text="Danger" type="button" v-bind:block="false"
      color="#FFFFFF" theme="theme--light01" v-bind:rotate="0" v-bind:squared="false" variant="danger"
      v-bind:isEnabled="true" background="#dc3545" linkTarget="_top" ncLinkType="router_link" borderColor="#dc3545"
      v-bind:resetTrigger="false" ncTooltipText="" verticalWidth="60px"
      v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'string','propName':'text','displayName':'Value'}]}"
      verticalHeight="60px" horizontalWidth="72.4479px" toForRouterLink="/" horizontalHeight="37.5347px"
      ncClickFontColor="#FFFFFF" ncFocusFontColor="#FFFFFF" ncHoverFontColor="#FFFFFF" ncClickBorderColor="#dc3545"
      ncDisableFontColor="#FFFFFF" ncFocusBorderColor="#dc3545" ncHoverBorderColor="#dc3545"
      ncDisableBorderColor="transparent" ncClickBackgroundColor="#dc3545" ncFocusBackgroundColor="#dc3545"
      ncHoverBackgroundColor="#dc3545" ncDisableBackgroundColor="#969696" position="relative"
      id="2ccb9fb7-3bcc-479a-a510-ccf25cf389f9"
      v-bind:style="{'width':'100%','filter':'none','height':'100%','tabIndex':'0px','boxShadow':'','fontStyle':'normal','marginTop':'0px','textAlign':'center','fontFamily':'Open Sans','fontWeight':700,'lineHeight':'1.4','marginLeft':'0px','paddingTop':'','textIndent':'0px','textShadow':'','visibility':'visible','whiteSpace':'pre-wrap','borderStyle':'solid','marginRight':'0px','paddingLeft':'','wordSpacing':'0px','marginBottom':'0px','mixBlendMode':'normal','paddingRight':'','letterSpacing':'0px','paddingBottom':'','textTransform':'none','backdropFilter':'none','borderTopWidth':'1px','textDecoration':'none','borderLeftWidth':'1px','borderRightWidth':'1px','horizontalHeight':'37.5347px','borderBottomWidth':'1px','borderTopLeftRadius':'4px','borderTopRightRadius':'4px','borderBottomLeftRadius':'4px','borderBottomRightRadius':'4px','zIndex':3}"/>
  </DropZone>
</template>
<script>
import { mapGetters } from 'vuex';
export default {
  name: 'Screen2',
  data() {
    return {};
  },
  props: {},
  created() {},
  mounted() {},
  computed: { ...mapGetters('source', ['getApiMappingWithChain'])},
  methods: {bindSource(chain) { return this.getApiMappingWithChain(chain); }},
  watch: {},
};
</script>

<style lang="scss" scoped>@media (min-width: 1024.05px){
[id='dcc8654f-40e9-4a19-9d4e-c4456ec2ab9e'] {
             display: grid; 
             grid-template-columns: 2.03125rem 13.8671875rem 5.46875rem 77.3828125rem 1.25rem;
             grid-template-rows: minmax(1.5625rem, max-content) minmax(38.59375rem, max-content) minmax(3.203125rem, max-content) minmax(2.421875rem, max-content) minmax(14.21875rem, max-content);
          }
[id='53821db8-c85f-4daa-b988-d1b7dcba64d2']{
          grid-area: 2/2/3/5;
          font-size: Max(Min(14rem, 12px),1.09375rem);
          }
[id='2ccb9fb7-3bcc-479a-a510-ccf25cf389f9']{
          grid-area: 4/3/5/4;
          font-size: Max(Min(12rem, 12px),0.9375rem);
          }
}
@media (min-width: 768.05px) and (max-width: 1024px){
[id='dcc8654f-40e9-4a19-9d4e-c4456ec2ab9e'] {
             display: grid; 
             grid-template-columns: 3.125rem 43.45703125rem 6.8359375rem 43.45703125rem 3.125rem;
             grid-template-rows: minmax(1.953125rem, max-content) minmax(37.40912762520194rem, max-content) minmax(4.00390625rem, max-content) minmax(3.02734375rem, max-content) minmax(3.125rem, max-content);
          }
[id='53821db8-c85f-4daa-b988-d1b7dcba64d2']{
          grid-area: 2/2/3/5;
          font-size: Max(Min(14rem, 12px),1.060177705977383rem);
          }
[id='2ccb9fb7-3bcc-479a-a510-ccf25cf389f9']{
          grid-area: 4/3/5/4;
          font-size: Max(Min(12rem, 12px),1.171875rem);
          }
}
@media (min-width: 480.05px) and (max-width: 768px){
[id='dcc8654f-40e9-4a19-9d4e-c4456ec2ab9e'] {
             display: grid; 
             grid-template-columns: 4.166666667000001rem 41.276041666333334rem 9.114583333333334rem 41.27604166633333rem 4.166666667000001rem;
             grid-template-rows: minmax(2.6041666666666665rem, max-content) minmax(36.577813677709216rem, max-content) minmax(5.338541666666667rem, max-content) minmax(4.036458333333333rem, max-content) minmax(4.166666667rem, max-content);
          }
[id='53821db8-c85f-4daa-b988-d1b7dcba64d2']{
          grid-area: 2/2/3/5;
          font-size: Max(Min(14rem, 12px),1.0366182013925689rem);
          }
[id='2ccb9fb7-3bcc-479a-a510-ccf25cf389f9']{
          grid-area: 4/3/5/4;
          font-size: Max(Min(12rem, 12px),1.5625rem);
          }
}
@media (min-width: 375.05px) and (max-width: 480px){
[id='dcc8654f-40e9-4a19-9d4e-c4456ec2ab9e'] {
             display: grid; 
             grid-template-columns: 5rem 37.708333333333336rem 14.583333333333334rem 37.70833333333333rem 5rem;
             grid-template-rows: minmax(4.166666666666667rem, max-content) minmax(35.91276252019386rem, max-content) minmax(8.541666666666666rem, max-content) minmax(6.458333333333333rem, max-content) minmax(5rem, max-content);
          }
[id='53821db8-c85f-4daa-b988-d1b7dcba64d2']{
          grid-area: 2/2/3/5;
          font-size: Max(Min(14rem, 12px),1.0177705977382874rem);
          }
[id='2ccb9fb7-3bcc-479a-a510-ccf25cf389f9']{
          grid-area: 4/3/5/4;
          font-size: Max(Min(12rem, 12px),2.5rem);
          }
}
@media (min-width: 0px) and (max-width: 375px){
[id='dcc8654f-40e9-4a19-9d4e-c4456ec2ab9e'] {
             display: grid; 
             grid-template-columns: 6.4rem 0 87.2rem 0 6.4rem;
             grid-template-rows: minmax(5.333333333333333rem, max-content) minmax(34.79547657512116rem, max-content) minmax(10.933333333333334rem, max-content) minmax(38.617142857142866rem, max-content) minmax(6.4rem, max-content);
          }
[id='53821db8-c85f-4daa-b988-d1b7dcba64d2']{
          grid-area: 2/3/3/4;
          font-size: Max(Min(14rem, 12px),0.9861066235864298rem);
          }
[id='2ccb9fb7-3bcc-479a-a510-ccf25cf389f9']{
          grid-area: 4/2/5/5;
          font-size: Max(Min(12rem, 12px),14.94857142857143rem);
          }
}
</style>