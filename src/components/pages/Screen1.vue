<template>
  <NucGridPage v-bind:gap="{'col':0,'row':0}" v-bind:rows="[1]"
    v-bind:schema="{'r0-c0':{'col':0,'row':0,'showIn':['xs','sm','md','lg'],'colSpan':1,'rowSpan':1}}"
    v-bind:columns="[1]" overflow="auto" v-bind:designMode="false" v-bind:minNsLimit="500"
    v-bind:style="{'background':'#FFFFFF','paddingTop':'0px','paddingLeft':'0px','paddingRight':'0px','paddingBottom':'0px'}">
    <NucGridCell v-bind:wrap="true" v-bind:reverse="false" overflow="hidden" direction="column"
      v-bind:showInDevice="['xs','sm','md','lg']" verticalAlignment="top" horizontalAlignment="left"
      id="dcea891c-bd60-4816-bbec-e5d96af48a6a" v-bind:col="0" v-bind:row="0" v-bind:colSpan="1" v-bind:rowSpan="1"
      v-bind:marginTop="0" v-bind:marginLeft="0" v-bind:marginRight="0" v-bind:marginBottom="0"
      v-bind:style="{'height':'auto','background':'transparent','paddingTop':'0px','borderColor':'','borderStyle':'solid','borderWidth':'0px','paddingLeft':'0px','borderRadius':'0px','paddingRight':'0px','paddingBottom':'0px','borderTopWidth':'0px','borderLeftWidth':'0px','borderRightWidth':'0px','borderBottomWidth':'0px','borderTopLeftRadius':'1px','borderTopRightRadius':'1px','borderBottomLeftRadius':'1px','borderBottomRightRadius':'1px'}"
      slot="r0-c0" area="r0-c0">
      <WAdvertisement v-bind:blank="true" imgSrc="" v-bind:overlay="true" cardText="Medium Rectangle" imgWidth="300px"
        bgVariant="secondary" imgHeight="300px" textVariant="white"
        v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'string','propName':'imgSrc','displayName':'ImageUrl'},{'type':'string','propName':'cardText','displayName':'Value'}]}"
        verticalPosition="align-items-center" horizontalPosition="justify-content-center" position="absolute"
        top="26.985865724381625%" left="32.119285714285716%" id="3c9fa4a0-b613-4619-bc5b-b0fe162674fb"
        v-bind:style="{'width':'262.5','height':'45','maxWidth':'','minWidth':'','marginTop':'0px','maxHeight':'','minHeight':'','marginLeft':'0px','paddingTop':'0px','marginRight':'0px','paddingLeft':'0px','marginBottom':'0px','paddingRight':'0px','paddingBottom':'0px','zIndex':2}"/>
      <WBlockquoteLabel text="— Author Name, Publication" theme="theme--light01" ncTypography="body1" ncTooltipText=""
        v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'string','propName':'text','displayName':'Value'}]}"
        position="absolute" top="58.07891637220259%" left="31.540714285714287%"
        id="78bf51d0-9376-4882-b40d-c69e1a5d25dc"
        v-bind:style="{'color':'gray','width':'','height':'','fontSize':'9px','maxWidth':'','minWidth':'','fontStyle':'normal','marginTop':'0px','maxHeight':'','minHeight':'','textAlign':'left','fontFamily':'Roboto-Regular,Roboto','fontWeight':'normal','lineHeight':'1.0499999999999998','marginLeft':'0px','paddingTop':'0px','textShadow':'','visibility':'visible','marginRight':'0px','paddingLeft':'0px','marginBottom':'0px','paddingRight':'0px','paddingBottom':'0px','textDecoration':'none','zIndex':3}"/>
      <WIconBreadcrumb rel="" href="" icon="house-fill" text="House" scale="" shift="" v-bind:active="false"
        v-bind:isIcon="true" v-bind:options="[]" v-bind:disabled="false" v-bind:selected="[]" v-bind:isEnabled="true"
        linkTarget="_self" visibility="visible" ariaCurrent="location" ncTypography="body1" ncTooltipText=""
        v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'string','propName':'text','displayName':'Value'}]}"
        ncClickFontColor="#FFFFFF" ncFocusFontColor="#FFFFFF" ncHoverFontColor="#FFFFFF" ncClickBorderColor="#4285f4"
        ncDisableFontColor="#FFFFFF" ncFocusBorderColor="#4285f4" ncHoverBorderColor="#4285f4"
        ncDisableBorderColor="transparent" ncClickBackgroundColor="#4285f4" ncFocusBackgroundColor="#4285f4"
        ncHoverBackgroundColor="#4285f4" ncDisableBackgroundColor="#969696" position="absolute" top="58.08833922261484%"
        left="36.04142857142857%" id="226712ed-5c62-48ee-a558-160113fda84c"
        v-bind:style="{'color':'#007bff','width':'','height':'','fontSize':'12px','maxWidth':'','minWidth':'','fontStyle':'normal','marginTop':'0px','maxHeight':'','minHeight':'','textAlign':'center','background':'#e9ecef','fontFamily':'Roboto-Regular,Roboto','fontWeight':'normal','marginLeft':'0px','paddingTop':'7.5px','visibility':'visible','marginRight':'0px','paddingLeft':'7.5px','marginBottom':'0px','paddingRight':'7.5px','paddingBottom':'7.5px','textDecoration':'none','zIndex':4}"/>
      <WBlockButton tag="button" href="" v-bind:pill="false" size="md" text="Block Level Button" type="button"
        v-bind:block="true" color="" theme="theme--light01" v-bind:squared="false" variant="primary"
        v-bind:isEnabled="true" background="" linkTarget="_self" ncLinkType="link" borderColor="007BFF"
        ncTypography="body1" v-bind:resetTrigger="false" ncTooltipText="" verticalWidth="60px"
        v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'string','propName':'text','displayName':'Value'}]}"
        verticalHeight="60px" horizontalWidth="72.4479px" toForRouterLink="to" horizontalHeight="37.5347px"
        ncClickFontColor="#FFFFFF" ncFocusFontColor="#FFFFFF" ncHoverFontColor="#FFFFFF" ncClickBorderColor="#007bff"
        ncDisableFontColor="#FFFFFF" ncFocusBorderColor="#007bff" ncHoverBorderColor="#007bff"
        ncDisableBorderColor="transparent" ncClickBackgroundColor="#007bff" ncFocusBackgroundColor="#007bff"
        ncHoverBackgroundColor="#007bff" ncDisableBackgroundColor="#969696" position="absolute"
        top="47.948174322732626%" left="0%" id="00482220-df25-40b4-92da-9e6a08e772f9"
        v-bind:style="{'width':'','height':'','fontSize':'9px','maxWidth':'','minWidth':'','tabIndex':'0px','boxShadow':'','fontStyle':'normal','marginTop':'0px','maxHeight':'','minHeight':'','textAlign':'center','fontFamily':'OpenSans-Bold,Open Sans','fontWeight':'bold','lineHeight':'1.0499999999999998','marginLeft':'0px','paddingTop':'','textShadow':'','visibility':'visible','borderStyle':'solid','marginRight':'0px','paddingLeft':'','marginBottom':'0px','paddingRight':'','paddingBottom':'','borderTopWidth':'0.75px','textDecoration':'none','borderLeftWidth':'0.75px','borderRightWidth':'0.75px','horizontalHeight':'28.151025px','borderBottomWidth':'0.75px','borderTopLeftRadius':'3px','borderTopRightRadius':'3px','borderBottomLeftRadius':'3px','borderBottomRightRadius':'3px','zIndex':5}"/>
      <WButton tag="button" href="" v-bind:pill="false" size="md" text="Button" type="button" v-bind:block="false"
        color="" theme="theme--light01" v-bind:squared="false" variant="primary" ncBgType="bgColor"
        v-bind:isEnabled="true" background="" linkTarget="_self" ncLinkType="link" borderColor="#007bff"
        ncTypography="body1" v-bind:resetTrigger="false" ncTooltipText="" verticalWidth="60px"
        v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'string','propName':'text','displayName':'Value'}]}"
        textDecoration="none" verticalHeight="60px" horizontalWidth="72.4479px" nucalScaleWidth="" toForRouterLink="to"
        horizontalHeight="37.5347px" ncClickFontColor="#FFFFFF" ncFocusFontColor="#FFFFFF" ncHoverFontColor="#FFFFFF"
        nucalScaleHeight="" ncClickBorderColor="#007BFF" ncDisableFontColor="#FFFFFF" ncFocusBorderColor="#007BFF"
        ncHoverBorderColor="#007BFF" ncDisableBorderColor="transparent" ncClickBackgroundColor="#007BFF"
        ncFocusBackgroundColor="#007BFF" ncHoverBackgroundColor="#007BFF" ncDisableBackgroundColor="#969696"
        position="absolute" top="69.37809187279152%" left="21.41%" id="14fbdc96-707e-4d2b-b598-803bac1a9047"
        v-bind:style="{'width':'','height':'','fontSize':'9px','maxWidth':'','minWidth':'','tabIndex':'0px','boxShadow':'','fontStyle':'normal','marginTop':'','maxHeight':'','minHeight':'','textAlign':'center','fontFamily':'OpenSans-Bold,Open Sans','fontWeight':'normal','lineHeight':'1.0499999999999998','marginLeft':'','paddingTop':'','textShadow':'','visibility':'visible','borderStyle':'solid','marginRight':'','paddingLeft':'','marginBottom':'','paddingRight':'','paddingBottom':'','borderTopWidth':'0.75px','textDecoration':'none','borderLeftWidth':'0.75px','borderRightWidth':'0.75px','horizontalHeight':'28.151025px','borderBottomWidth':'0.75px','borderTopLeftRadius':'3px','borderTopRightRadius':'3px','borderBottomLeftRadius':'3px','borderBottomRightRadius':'3px','zIndex':6}"/>
      <WDangerButton tag="button" href="" v-bind:pill="false" size="md" text="Danger" type="button" v-bind:block="false"
        color="" theme="theme--light01" v-bind:squared="false" variant="danger" v-bind:isEnabled="true" background=""
        linkTarget="_self" ncLinkType="link" borderColor="#DC3545" ncTypography="body1" v-bind:resetTrigger="false"
        ncTooltipText="" verticalWidth="60px"
        v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'string','propName':'text','displayName':'Value'}]}"
        verticalHeight="60px" horizontalWidth="72.4479px" toForRouterLink="to" horizontalHeight="37.5347px"
        ncClickFontColor="#FFFFFF" ncFocusFontColor="#FFFFFF" ncHoverFontColor="#FFFFFF" ncClickBorderColor="#dc3545"
        ncDisableFontColor="#FFFFFF" ncFocusBorderColor="#dc3545" ncHoverBorderColor="#dc3545"
        ncDisableBorderColor="transparent" ncClickBackgroundColor="#dc3545" ncFocusBackgroundColor="#dc3545"
        ncHoverBackgroundColor="#dc3545" ncDisableBackgroundColor="#969696" position="absolute" top="57.13427561837456%"
        left="17.757857142857144%" id="70f84aae-7b24-41c4-a45a-6ee2284b46d8"
        v-bind:style="{'width':'','height':'','fontSize':'9px','maxWidth':'','minWidth':'','tabIndex':'0px','boxShadow':'','fontStyle':'normal','marginTop':'0px','maxHeight':'','minHeight':'','textAlign':'center','fontFamily':'OpenSans-Bold,Open Sans','fontWeight':'bold','lineHeight':'1.0499999999999998','marginLeft':'0px','paddingTop':'','textShadow':'','visibility':'visible','borderStyle':'solid','marginRight':'0px','paddingLeft':'','marginBottom':'0px','paddingRight':'','paddingBottom':'','borderTopWidth':'0.75px','textDecoration':'none','borderLeftWidth':'0.75px','borderRightWidth':'0.75px','horizontalHeight':'28.151025px','borderBottomWidth':'0.75px','borderTopLeftRadius':'3px','borderTopRightRadius':'3px','borderBottomLeftRadius':'3px','borderBottomRightRadius':'3px','zIndex':7}"/>
      <WDangerWithButton tag="button" href="" v-bind:pill="false" size="md" text="Button" type="button"
        v-bind:block="false" color="" theme="theme--light01" v-bind:squared="false" variant="danger"
        v-bind:isEnabled="true" background="" linkTarget="_self" ncLinkType="link" borderColor="#DC3545"
        ncTypography="body1" v-bind:resetTrigger="false" ncTooltipText="" verticalWidth="60px"
        v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'string','propName':'text','displayName':'Value'}]}"
        verticalHeight="60px" horizontalWidth="72.4479px" toForRouterLink="to" horizontalHeight="37.5347px"
        ncClickFontColor="#FFFFFF" ncFocusFontColor="#FFFFFF" ncHoverFontColor="#FFFFFF" ncClickBorderColor="#dc3545"
        ncDisableFontColor="#FFFFFF" ncFocusBorderColor="#dc3545" ncHoverBorderColor="#dc3545"
        ncDisableBorderColor="transparent" ncClickBackgroundColor="#dc3545" ncFocusBackgroundColor="#dc3545"
        ncHoverBackgroundColor="#dc3545" ncDisableBackgroundColor="#969696" position="absolute" top="33.10600706713781%"
        left="24.59642857142857%" id="6f165a5b-d308-4449-8756-c1ba2c8eacb1"
        v-bind:style="{'width':'','height':'','fontSize':'9px','maxWidth':'','minWidth':'','tabIndex':'0px','boxShadow':'','fontStyle':'normal','marginTop':'0px','maxHeight':'','minHeight':'','textAlign':'center','fontFamily':'OpenSans-Bold,Open Sans','fontWeight':'bold','lineHeight':'1.0499999999999998','marginLeft':'0px','paddingTop':'','textShadow':'','visibility':'visible','borderStyle':'solid','marginRight':'0px','paddingLeft':'','marginBottom':'0px','paddingRight':'','paddingBottom':'','borderTopWidth':'0.75px','textDecoration':'none','borderLeftWidth':'0.75px','borderRightWidth':'0.75px','horizontalHeight':'28.151025px','borderBottomWidth':'0.75px','borderTopLeftRadius':'3px','borderTopRightRadius':'3px','borderBottomLeftRadius':'3px','borderBottomRightRadius':'3px','zIndex':8}"/>
      <WSquaredDarkButton tag="button" href="" v-bind:pill="false" size="md" text="Dark" type="button"
        v-bind:block="false" color="" theme="theme--light01" v-bind:squared="true" variant="dark"
        v-bind:isEnabled="true" background="" linkTarget="_self" ncLinkType="link" borderColor="#343A40"
        ncTypography="body1" v-bind:resetTrigger="false" ncTooltipText="" verticalWidth="60px"
        v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'string','propName':'text','displayName':'Value'}]}"
        verticalHeight="60px" horizontalWidth="72.4479px" nucalScaleWidth="" toForRouterLink="to"
        horizontalHeight="37.5347px" ncClickFontColor="#FFFFFF" ncFocusFontColor="#FFFFFF" ncHoverFontColor="#FFFFFF"
        nucalScaleHeight="" ncClickBorderColor="#343A40" ncDisableFontColor="#FFFFFF" ncFocusBorderColor="#343A40"
        ncHoverBorderColor="#343A40" ncDisableBorderColor="transparent" ncClickBackgroundColor="#343A40"
        ncFocusBackgroundColor="#343A40" ncHoverBackgroundColor="#343A40" ncDisableBackgroundColor="#969696"
        position="absolute" top="38.522968197879855%" left="53.12%" id="7e37daa8-2ef6-4daa-b2a0-3f67613e6423"
        v-bind:style="{'width':'','height':'','fontSize':'9px','maxWidth':'','minWidth':'','tabIndex':'0px','boxShadow':'','fontStyle':'normal','marginTop':'0px','maxHeight':'','minHeight':'','textAlign':'center','fontFamily':'OpenSans-Bold,Open Sans','fontWeight':'bold','lineHeight':'1.0499999999999998','marginLeft':'0px','paddingTop':'','textShadow':'','visibility':'visible','borderStyle':'solid','marginRight':'0px','paddingLeft':'','marginBottom':'0px','paddingRight':'','paddingBottom':'','borderTopWidth':'0.75px','textDecoration':'none','borderLeftWidth':'0.75px','borderRightWidth':'0.75px','horizontalHeight':'28.151025px','borderBottomWidth':'0.75px','borderTopLeftRadius':'3px','borderTopRightRadius':'3px','borderBottomLeftRadius':'3px','borderBottomRightRadius':'3px','zIndex':9}"/>
      <WCalendar v-bind:fade="false" text="Text Content 1" theme="theme--light01" ImgAlt="Blank Image 1"
        v-bind:noWrap="false" caption="Carousel 1" v-bind:noTouch="false"
        imageUrl="https://picsum.photos/500/250/?image=1082" v-bind:interval="5000" v-bind:isEnabled="true"
        background="" blankColor="#ababab" v-bind:indicators="false" secondText="Text Content 2"
        v-bind:noAnimation="false" ncTypography="body2" v-bind:noHoverPause="false" secondImgAlt="Blank Image 2"
        secondCaption="Carousel 2"
        v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'string','propName':'imageUrl','displayName':'ImageUrl'},{'type':'string','propName':'secondImageUrl','displayName':'SecondImageUrl'}]}"
        secondImageUrl="https://picsum.photos/500/250/?image=1002" ncClickBorderColor="black" ncHoverBorderColor="black"
        dataModelForDynamicType="string" position="absolute" top="25.10482921083628%" left="19.620714285714286%"
        id="becbd14c-2aed-4a84-88d9-20cdaf728817"
        v-bind:style="{'width':'','height':'','fontSize':'9px','maxWidth':'','minWidth':'','boxShadow':'','fontStyle':'normal','marginTop':'0px','maxHeight':'','minHeight':'','fontFamily':'OpenSans-Bold,Open Sans','marginLeft':'0px','paddingTop':'0px','textShadow':'','visibility':'visible','marginRight':'0px','paddingLeft':'0px','marginBottom':'0px','paddingRight':'0px','paddingBottom':'0px','borderTopWidth':'0px','borderLeftWidth':'0px','borderRightWidth':'0px','borderBottomWidth':'0px','borderTopLeftRadius':'0px','borderTopRightRadius':'0px','borderBottomLeftRadius':'0px','borderBottomRightRadius':'0px','zIndex':10}"/>
      <WDateInput id="b075f17e-3bd0-4ba9-9d35-9bbe77d80adf" v-bind:lazy="false" size="md" text="" v-bind:trim="false"
        v-bind:noWheel="false" v-bind:disabled="false" v-bind:readonly="false" v-bind:required="false" wordList=""
        v-bind:autofocus="false" v-bind:plaintext="false" background="" ariaInvalid="false" v-bind:debounceVal="0"
        ncInputType="date" placeholder="" v-bind:previewMode="true" autocomplete="" ncTypography="body1"
        v-bind:lazyFormatter="false" ncTooltipText="" v-bind:isWordListOpen="false"
        v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':true,'structure':[{'type':'string','ncKey':'type','ncType':{'ncInputType':'number'},'ncValue':'number','propName':'text','displayName':'Value','nsDefaultValue':'string'}]}"
        v-bind:isNumberConvert="false" ncClickFontColor="#434855" ncFocusFontColor="#434855" ncHoverFontColor="#434855"
        ncMaxNumberValue="100" ncMinNumberValue="0" ncClickBorderColor="#000000" ncDisableFontColor="#434855"
        ncFocusBorderColor="#000000" ncHoverBorderColor="#000000" ncDisableBorderColor="#000000"
        formatterFunctionName="" ncClickBackgroundColor="#ffffff" ncFocusBackgroundColor="#ffffff"
        ncHoverBackgroundColor="#ffffff" ncDisableBackgroundColor="#ffffff" position="absolute" top="32.64193168433451%"
        left="76.31928571428571%"
        v-bind:style="{'color':'','width':'','height':'','fontSize':'9px','maxWidth':'','minWidth':'','boxShadow':'','fontStyle':'normal','marginTop':'0px','maxHeight':'','minHeight':'','textAlign':'left','fontFamily':'Roboto-Regular,Roboto','fontWeight':'normal','lineHeight':'0.75','marginLeft':'0px','paddingTop':'0px','visibility':'visible','borderColor':'#D1D1D6','borderStyle':'solid','marginRight':'0px','paddingLeft':'0px','marginBottom':'0px','paddingRight':'0px','paddingBottom':'0px','textDecoration':'none','zIndex':11}"/>
      <WButtonCheckbox size="sm" label="Button Check" v-bind:plain="false" theme="theme--light01" v-bind:value="false"
        v-bind:button="true" v-bind:inline="false" fontSize="14px" v-bind:autofocus="false" v-bind:isEnabled="true"
        textAlign="left" fontFamily="Roboto-Regular,Roboto" fontWeight="normal" ncTypography="custom"
        v-bind:indeterminate="false" labelPosition="right" ncTooltipText="" v-bind:checkboxSwitch="true"
        v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'boolean','propName':'value','displayName':'Value'},{'type':'string','propName':'label','displayName':'Display'}]}"
        ncFocusFontColor="black" ncHoverFontColor="black" ncDisableFontColor="black" ncFocusBorderColor="black"
        ncHoverBorderColor="black" ncDisableBorderColor="black" ncFocusBackgroundColor="transparent"
        ncHoverBackgroundColor="transparent" ncDisableBackgroundColor="transparent" position="absolute"
        top="83.63957597173145%" left="38.47142857142857%" id="74a0641c-4451-4a71-a3b6-da52d7ee713f"
        v-bind:style="{'color':'','width':'','height':'','maxWidth':'','minWidth':'','tabIndex':'0px','boxShadow':'','fontStyle':'none','marginTop':'0px','maxHeight':'','minHeight':'','lineHeight':'','marginLeft':'0px','paddingTop':'0px','textShadow':'','visibility':'visible','marginRight':'0px','paddingLeft':'0px','marginBottom':'0px','paddingRight':'0px','paddingBottom':'0px','textDecoration':'none','zIndex':12}"/>
      <WDefaultCheckbox size="md" label="I accept the terms and use" v-bind:plain="false" theme="theme--light01"
        v-bind:value="true" v-bind:inline="false" fontSize="14px" v-bind:autofocus="false" v-bind:isEnabled="true"
        textAlign="left" fontFamily="Roboto-Regular,Roboto" fontWeight="normal" ncTypography="custom"
        v-bind:indeterminate="false" labelPosition="right" ncTooltipText="" v-bind:checkboxSwitch="true"
        v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'boolean','propName':'value','displayName':'Value'},{'type':'string','propName':'label','displayName':'Display'}]}"
        ncFocusFontColor="black" ncHoverFontColor="black" ncDisableFontColor="black" ncFocusBorderColor="black"
        ncHoverBorderColor="black" ncDisableBorderColor="black" ncFocusBackgroundColor="transparent"
        ncHoverBackgroundColor="transparent" ncDisableBackgroundColor="transparent" position="absolute"
        top="78.68786808009423%" left="13.309285714285714%" id="882faf75-58b6-410a-bc5e-d30b47226454"
        v-bind:style="{'color':'','width':'','height':'','maxWidth':'','minWidth':'','tabIndex':'0px','boxShadow':'','fontStyle':'none','marginTop':'0px','maxHeight':'','minHeight':'','lineHeight':'','marginLeft':'0px','paddingTop':'0px','textShadow':'','visibility':'visible','marginRight':'0px','paddingLeft':'0px','marginBottom':'0px','paddingRight':'0px','paddingBottom':'0px','textDecoration':'none','zIndex':13}"/>
      <WCarousel v-bind:fade="false" text="Text Content 1" ImgAlt="Blank Image 1" v-bind:noWrap="false"
        caption="Carousel 1" v-bind:noTouch="false" imageUrl="https://picsum.photos/500/250/?image=1082"
        v-bind:interval="5000" v-bind:isEnabled="true" background="" blankColor="#ababab" v-bind:indicators="false"
        secondText="Text Content 2" v-bind:noAnimation="false" v-bind:noHoverPause="false" secondImgAlt="Blank Image 2"
        secondCaption="Carousel 2"
        v-bind:nucalDataModel="{'type':'NSW','isList':false,'dynamic':false,'structure':[{'type':'string','propName':'imageUrl','displayName':'ImageUrl'},{'type':'string','propName':'secondImageUrl','displayName':'SecondImageUrl'}]}"
        secondImageUrl="https://picsum.photos/500/250/?image=1002" ncClickBorderColor="black" ncHoverBorderColor="black"
        dataModelForDynamicType="string" position="absolute" top="64.67491166077738%" left="58.39857142857143%"
        id="a4fd8590-1cc4-4172-a7a5-7dcb5c152301"
        v-bind:style="{'width':'375px','height':'187.5px','maxWidth':'','minWidth':'','boxShadow':'','marginTop':'0px','maxHeight':'','minHeight':'','marginLeft':'0px','paddingTop':'0px','textShadow':'','visibility':'visible','marginRight':'0px','paddingLeft':'0px','marginBottom':'0px','paddingRight':'0px','paddingBottom':'0px','borderTopWidth':'0px','borderLeftWidth':'0px','borderRightWidth':'0px','borderBottomWidth':'0px','borderTopLeftRadius':'0px','borderTopRightRadius':'0px','borderBottomLeftRadius':'0px','borderBottomRightRadius':'0px','zIndex':14}"/>
    </NucGridCell>
  </NucGridPage>
</template>
<script>
export default {
  name: 'Screen1',
  data() {
    return {};
  },
  props: {},
  created() {},
  mounted() {},
  computed: {},
  methods: {},
  watch: {},
};
</script>

<style scoped></style>