<template>
	<div class="scroll-view-wrapper">
		<div class="scroll-view">
			<div class = "contact-page">
				<h3 class="home-case-title">
					关于我们 <em>About Us</em>
				</h3>
				<img :src="contactImg"/>
				<p>北京优艺客文化传播有限公司旗下的设计师交流平台，专为热爱界面设计的你而倾力打造。这里拥有最无敌的创意、最精美的视觉、最具国际化的意识和前瞻性思维！也许在不知不觉中，它将成为你设计路上的一位好伙伴，在你最需要灵感的时候给予你帮助，鼓励你不断向前。当然，我们也需要最热心的你为我们平台注入源源不断的新鲜血液。 ,我们都有相应解决的方法。我们的优势在于我们重视于每一份业务的设计质量，而不在意业务的数量多少，提升客户网站形象是我们致力追求的业务目标。</p>
				<p>专为热爱界面设计的你而倾力打造。这里拥有最无敌的创意、最精美的视觉、最具国际化的意识和前瞻性思维！也许在不知不觉中，它将成为你设计路上的一位好伙伴，在你最需要灵感的时候给予你帮助，鼓励你不断向前。当然，我们也需要最热心的你为我们平台注入源源不断的新鲜血液。 ,我们都有相应解决的方法优势在于我们重视于每一份业务的设计质量，而不在意业务的数量多少，提升客户网站形象是我们致力追求的业务目标。</p>
			</div>
		</div>
  </div>
</template>

<script>
	
  import contactImg from './images/contact.jpg'
	
	export  default {
  	data () {
  		
  		return {
  			contactImg
		  }
  		
	  }
	}
</script>