<template>
	<div class="container">
		<form @submit.prevent="submitForm">
			<div>
				<label for="name">이름</label>
				<input type="text" id="name" v-model="name" />
			</div>
			<div>
				<label for="password">비밀번호</label>
				<input type="password" id="password" v-model="password" />
			</div>
			<div>
				<label for="passwordConfirm">비밀번호 확인</label>
				<input type="password" id="passwordConfirm" v-model="passwordConfirm" />
			</div>
			<button type="submit">회원가입</button>
		</form>
	</div>
</template>

<script>
export default{
	name: 'SignupForm',
	data() {
		return {
			email: '',
			name: '',
			password: '',
			passwordConfirm: '',
			position: '',
			teamName: '',
		};
	},
	methods: {
		submitForm() {
			console.log('dd');
		},
	}
};
</script>

<style scoped>

</style>