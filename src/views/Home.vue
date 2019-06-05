<template>
	<mdb-container class="pt-5">
		<mdb-row class="justify-content-md-center">
		<mdb-col sm="12" md="12" lg="6">
				<mdb-card wide>
					<mdb-view hover cascade>
						<a href="#!">
							<mdb-card-image src="https://mdbootstrap.com/img/Photos/Others/photo10.jpg" alt="Card image cap" ></mdb-card-image>
							<mdb-mask flex-center waves overlay="white-slight"></mdb-mask>
						</a>
					</mdb-view>
					<mdb-card-body class="text-center" cascade>
						<mdb-card-title><strong>Serverless Architecture in AWS</strong></mdb-card-title>
						<h5 class="blue-text"><strong>Gerald Yerden II</strong></h5>
						<mdb-card-text>Serverless Application Model (SAM) vs Terraform</mdb-card-text>
						<a class="icons-sm li-ic pr-2" href="https://www.linkedin.com/in/gerald-yerden-ii-7a920178/" target="_blank" ><mdb-icon fab icon="linkedin" /></a>
						<a class="icons-sm tw-ic" href="https://twitter.com/dev_hulk" target="_blank"><mdb-icon fab icon="twitter" /></a>
					</mdb-card-body>
				</mdb-card>
		</mdb-col>
		</mdb-row>
	</mdb-container>
</template>
<script>
	import { mdbContainer, mdbRow, mdbCol, mdbCard, mdbCardImage, mdbCardHeader, mdbCardBody, mdbCardTitle, mdbCardText, mdbCardFooter, mdbCardUp, mdbCardAvatar, mdbCardGroup, mdbBtn, mdbView, mdbMask, mdbIcon } from 'mdbvue';
	export default {
		name: 'home',
		components: {
			mdbContainer,
			mdbRow,
			mdbCol,
			mdbCard,
			mdbCardImage,
			mdbCardHeader,
			mdbCardBody,
			mdbCardTitle,
			mdbCardText,
			mdbCardFooter,
			mdbCardUp,
			mdbCardAvatar,
			mdbCardGroup,
			mdbBtn,
			mdbView,
			mdbMask,
			mdbIcon
		}
	}

</script>
