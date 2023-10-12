<template>
  <DropZone ncBgType="bgColor" backgroundImage="" id="1134fbc0-a760-4715-bbdf-2ef05bebe10e"
    v-bind:style="{'width':'100%','height':'auto'}">
    <AdvanceDatatable
      v-bind:items="[{'id':'3458764518514816052','type':'card','title':'Simple !&amp;#39^!&amp;#39&amp;#43!&amp;#39%ard','description':'','x':0,'rotation':0,'y':0,'scale':1,'style':{'backgroundColor':'#2399f3'},'createdAt':'2022-02-09T12:15:59Z','createdBy':{'type':'user','name':'NucalVelocity','id':'3458764518389392033'},'modifiedAt':'2022-02-09T12:15:59Z','modifiedBy':{'type':'user','name':'NucalVelocity','id':'3458764518389392033'},'capabilities':{'editable':true}}]"
      v-bind:fields="[{'label':'Id','key':'id','sortable':true,'searchable':true,'class':''},{'label':'Type','key':'type','sortable':true,'searchable':true,'class':''},{'label':'Title','key':'title','sortable':true,'searchable':true,'class':''},{'label':'Description','key':'description','sortable':true,'searchable':true,'class':''},{'label':'X','key':'x','sortable':true,'searchable':true,'class':''},{'label':'Rotation','key':'rotation','sortable':true,'searchable':true,'class':''},{'label':'Y','key':'y','sortable':true,'searchable':true,'class':''},{'label':'Scale','key':'scale','sortable':true,'searchable':true,'class':''},{'label':'Style','key':'style','sortable':true,'searchable':true,'class':''},{'label':'CreatedAt','key':'createdAt','sortable':true,'searchable':true,'class':''},{'label':'CreatedBy','key':'createdBy','sortable':true,'searchable':true,'class':''},{'label':'ModifiedAt','key':'modifiedAt','sortable':true,'searchable':true,'class':''},{'label':'ModifiedBy','key':'modifiedBy','sortable':true,'searchable':true,'class':''},{'label':'Capabilities','key':'capabilities','sortable':true,'searchable':true,'class':''}]"
      v-bind:isBusy="false" v-bind:isFixed="true" v-bind:isHover="false" v-bind:perPage="5"
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
      v-bind:snapX="false" v-bind:snapY="false" id="35838044-9cfa-4c75-aef3-ba7aa43a0efc"
      v-bind:style="{'color':'#606060','width':'100%','height':'100%','minWidth':'350px','fontStyle':'normal','minHeight':'150px','textAlign':'left','wordBreak':'keep-all','background':'#FFFFFF','fontFamily':'Inter','fontWeight':400,'textIndent':'0px','visibility':'visible','whiteSpace':'nowrap','wordSpacing':'0px','letterSpacing':'0px','textTransform':'none','zIndex':2}"/>
    <AdvanceDatatable v-bind:items="bindSource('functions.getAllDevices.data')"
      v-bind:fields="[{'label':'Id','key':'id','sortable':true,'searchable':true,'class':''},{'label':'Policies','key':'policies','sortable':true,'searchable':true,'class':''}]"
      v-bind:isBusy="false" v-bind:isFixed="true" v-bind:isHover="false" mapping="functions.getAllDevices.data"
      v-bind:perPage="5" emptyTxt="This datatable is currently empty, but you can customize it with your information."
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
      v-bind:snapX="false" v-bind:snapY="false" id="0a8f3391-38e9-4a0d-93a0-9a0a0bec1f5d"
      v-bind:style="{'color':'#606060','width':'100%','height':'100%','minWidth':'350px','fontStyle':'normal','minHeight':'150px','textAlign':'left','wordBreak':'keep-all','background':'#FFFFFF','fontFamily':'Inter','fontWeight':400,'textIndent':'0px','visibility':'visible','whiteSpace':'nowrap','wordSpacing':'0px','letterSpacing':'0px','textTransform':'none','zIndex':3}"/>
    <WButton tag="button" href="" v-bind:pill="false" size="md" text="Button" type="button" v-bind:block="false"
      color="#FFFFFF" theme="theme--light01" v-bind:rotate="0" v-bind:squared="false" variant="primary"
      ncBgType="bgColor" v-bind:isEnabled="true" background="#007bff" linkTarget="_top" ncLinkType="router_link"
      borderColor="#007bff" v-bind:resetTrigger="false" ncTooltipText="" verticalWidth="60px"
      v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'string','propName':'text','displayName':'Value'}]}"
      verticalHeight="60px" horizontalWidth="72.4479px" nucalScaleWidth="" toForRouterLink="Screen+2"
      horizontalHeight="37.5347px" ncClickFontColor="#FFFFFF" ncFocusFontColor="#FFFFFF" ncHoverFontColor="#FFFFFF"
      nucalScaleHeight="" ncClickBorderColor="#007BFF" ncDisableFontColor="#FFFFFF" ncFocusBorderColor="#007BFF"
      ncHoverBorderColor="#007BFF" ncDisableBorderColor="transparent" ncClickBackgroundColor="#007BFF"
      ncFocusBackgroundColor="#007BFF" ncHoverBackgroundColor="#007BFF" ncDisableBackgroundColor="#969696"
      position="relative" id="65dd5638-8537-4db3-afb8-daa8246a241c"
      v-bind:style="{'width':'100%','filter':'none','height':'100%','tabIndex':'0px','boxShadow':'','fontStyle':'normal','marginTop':'','textAlign':'center','fontFamily':'Open Sans','fontWeight':700,'lineHeight':'1.4','marginLeft':'','paddingTop':'','textIndent':'0px','textShadow':'','visibility':'visible','whiteSpace':'pre-wrap','borderStyle':'solid','marginRight':'','paddingLeft':'','wordSpacing':'0px','marginBottom':'','mixBlendMode':'normal','paddingRight':'','letterSpacing':'0px','paddingBottom':'','textTransform':'none','backdropFilter':'none','borderTopWidth':'1px','textDecoration':'none','borderLeftWidth':'1px','borderRightWidth':'1px','horizontalHeight':'37.5347px','borderBottomWidth':'1px','borderTopLeftRadius':'4px','borderTopRightRadius':'4px','borderBottomLeftRadius':'4px','borderBottomRightRadius':'4px','zIndex':4}"/>
  </DropZone>
</template>
<script>
import { mapGetters } from 'vuex';
export default {
  name: 'Screen1',
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
[id='1134fbc0-a760-4715-bbdf-2ef05bebe10e'] {
             display: grid; 
             grid-template-columns: 0.625rem 6.6796875rem 5.3125rem 9.21875rem 51.640625rem 1.7578125rem 24.765625rem;
             grid-template-rows: minmax(2.34375rem, max-content) minmax(28.125rem, max-content) minmax(1.796875rem, max-content) minmax(6.796875rem, max-content) minmax(2.421875rem, max-content) minmax(20.15625rem, max-content) minmax(2.578125rem, max-content);
          }
[id='35838044-9cfa-4c75-aef3-ba7aa43a0efc']{
          grid-area: 2/2/3/7;
          font-size: Max(Min(14rem, 12px),1.09375rem);
          }
[id='0a8f3391-38e9-4a0d-93a0-9a0a0bec1f5d']{
          grid-area: 4/5/7/6;
          font-size: Max(Min(14rem, 12px),1.09375rem);
          }
[id='65dd5638-8537-4db3-afb8-daa8246a241c']{
          grid-area: 5/3/6/4;
          font-size: Max(Min(12rem, 12px),0.9375rem);
          }
}
@media (min-width: 768.05px) and (max-width: 1024px){
[id='1134fbc0-a760-4715-bbdf-2ef05bebe10e'] {
             display: grid; 
             grid-template-columns: 3.125rem 9.716796875rem 6.640625rem 3.125rem 64.55078125rem 9.716796875rem 3.125rem;
             grid-template-rows: minmax(2.9296875rem, max-content) minmax(35.340314136125656rem, max-content) minmax(2.24609375rem, max-content) minmax(8.49609375rem, max-content) minmax(3.02734375rem, max-content) minmax(25.1953125rem, max-content) minmax(3.125rem, max-content);
          }
[id='35838044-9cfa-4c75-aef3-ba7aa43a0efc']{
          grid-area: 2/2/3/7;
          font-size: Max(Min(14rem, 12px),1.3743455497382198rem);
          }
[id='0a8f3391-38e9-4a0d-93a0-9a0a0bec1f5d']{
          grid-area: 4/5/7/6;
          font-size: Max(Min(14rem, 12px),1.3671875rem);
          }
[id='65dd5638-8537-4db3-afb8-daa8246a241c']{
          grid-area: 5/3/6/4;
          font-size: Max(Min(12rem, 12px),1.171875rem);
          }
}
@media (min-width: 480.05px) and (max-width: 768px){
[id='1134fbc0-a760-4715-bbdf-2ef05bebe10e'] {
             display: grid; 
             grid-template-columns: 4.166666667rem 2.7994791663333345rem 38.60677083333333rem 8.854166666666666rem 38.606770833333336rem 2.7994791663333416rem 4.166666667rem;
             grid-template-rows: minmax(3.90625rem, max-content) minmax(34.554973821738216rem, max-content) minmax(2.9947916666666665rem, max-content) minmax(4.036458333333333rem, max-content) minmax(4.166666667rem, max-content) minmax(48.95833333333333rem, max-content) minmax(4.166666667rem, max-content);
          }
[id='35838044-9cfa-4c75-aef3-ba7aa43a0efc']{
          grid-area: 2/2/3/7;
          font-size: Max(Min(14rem, 12px),1.343804537512042rem);
          }
[id='0a8f3391-38e9-4a0d-93a0-9a0a0bec1f5d']{
          grid-area: 6/3/7/6;
          font-size: Max(Min(14rem, 12px),1.8229166666666667rem);
          }
[id='65dd5638-8537-4db3-afb8-daa8246a241c']{
          grid-area: 4/4/5/5;
          font-size: Max(Min(12rem, 12px),1.5625rem);
          }
}
@media (min-width: 375.05px) and (max-width: 480px){
[id='1134fbc0-a760-4715-bbdf-2ef05bebe10e'] {
             display: grid; 
             grid-template-columns: 5rem 0 40.37065052950076rem 9.258698940998485rem 40.37065052950076rem 0 5rem;
             grid-template-rows: minmax(6.25rem, max-content) minmax(33.92670157068063rem, max-content) minmax(4.791666666666667rem, max-content) minmax(4.220877458396369rem, max-content) minmax(3.2677760968229954rem, max-content) minmax(51.195158850226925rem, max-content) minmax(5rem, max-content);
          }
[id='35838044-9cfa-4c75-aef3-ba7aa43a0efc']{
          grid-area: 2/2/3/7;
          font-size: Max(Min(14rem, 12px),1.319371727748691rem);
          }
[id='0a8f3391-38e9-4a0d-93a0-9a0a0bec1f5d']{
          grid-area: 6/3/7/6;
          font-size: Max(Min(14rem, 12px),1.906202723146747rem);
          }
[id='65dd5638-8537-4db3-afb8-daa8246a241c']{
          grid-area: 4/4/5/5;
          font-size: Max(Min(12rem, 12px),1.6338880484114977rem);
          }
}
@media (min-width: 0px) and (max-width: 375px){
[id='1134fbc0-a760-4715-bbdf-2ef05bebe10e'] {
             display: grid; 
             grid-template-columns: 6.4rem 0 39.11467473524962rem 8.970650529500757rem 39.11467473524962rem 0 6.4rem;
             grid-template-rows: minmax(8rem, max-content) minmax(32.87120418848168rem, max-content) minmax(6.133333333333334rem, max-content) minmax(4.089561270801816rem, max-content) minmax(3.1661119515885026rem, max-content) minmax(49.60242057488654rem, max-content) minmax(6.4rem, max-content);
          }
[id='35838044-9cfa-4c75-aef3-ba7aa43a0efc']{
          grid-area: 2/2/3/7;
          font-size: Max(Min(14rem, 12px),1.278324607329843rem);
          }
[id='0a8f3391-38e9-4a0d-93a0-9a0a0bec1f5d']{
          grid-area: 6/3/7/6;
          font-size: Max(Min(14rem, 12px),1.8468986384266264rem);
          }
[id='65dd5638-8537-4db3-afb8-daa8246a241c']{
          grid-area: 4/4/5/5;
          font-size: Max(Min(12rem, 12px),1.5830559757942513rem);
          }
}
</style>