<template>
<section class="forms-section">
        <h1 class="section-title">Inscription à un Evénement</h1>
        <div class="forms">


            <div class="form-wrapper">
                <button type="button" class="switcher switcher-signup">
                    Inscription
                    <span class="underline"></span>
                </button>
                <form class="form form-signup">
                    <fieldset>
                        <legend>Veuillez remplir les champs pour participer à un événement <br>(réservé aux Skoonner).</legend>
                        <div class="input-block">
                            <label for="signup-pseudo">Pseudo</label>
                            <input id="signup-pseudo" type="text" required>
                        </div>
                        <div class="input-block">
                            <label for="signup-password">Mot de passe</label>
                            <input id="signup-password" type="password" required>
                        </div>
                        <div class="input-block">
                            <label for="signup-evenement">N° Evénement</label>
                            <input id="signup-evenement" type="text" required>
                        </div>
                        <div class="input-block">
                            <label for="signup-role">Rôle</label>
                            <input id="signup-role" type="text" required>
                        </div>

                    </fieldset>
                    <button type="submit" class="btn-signup">Envoyer</button>
                </form>
            </div>
        </div>
    </section>

</template>

<script>

export default {
    name: 'InscriptionEven'
}


</script>

<style scoped>

*,
*::before,
*::after {
	box-sizing: border-box;
}

body {
	margin: 0;
	font-family: Prompt, -apple-system, 'Helvetica Neue', 'Segoe UI', Arial, sans-serif;
	background: #f1f1f1;
}

.forms-section {
	display: flex;
	flex-direction: column;
	justify-content: center;
	align-items: center;
}

.section-title {
	font-size: 32px;
	letter-spacing: 1px;
	color: #49ada1;
}

.forms {
	display: flex;
	align-items: flex-start;
	margin-top: 30px;
}
.form {
	overflow: hidden;
	min-width: 260px;
	margin-top: 50px;
	padding: 30px 25px;
  border-radius: 5px;
	transform-origin: top;
}
.switcher {
	position: relative;
	cursor: pointer;
	display: block;
	margin-right: auto;
	margin-left: auto;
	padding: 0;
	text-transform: uppercase;
	font-family: inherit;
	font-size: 16px;
	letter-spacing: .5px;
	color: #a94d19;
	background-color: transparent;
	border: none;
	outline: none;

}

.underline {
	position: absolute;
	bottom: -5px;
	left: 0;
	overflow: hidden;
	pointer-events: none;
	width: 100%;
	height: 2px;
}

.underline::before {
	content: '';
	position: absolute;
	top: 0;
	left: inherit;
	display: block;
	width: inherit;
	height: inherit;
	background-color: currentColor;
	transition: transform .2s ease-out;
}

.form-wrapper {
	animation: hideLayer .3s ease-out forwards;
}

.form-wrapper.is-active {
	animation: showLayer .3s ease-in forwards;
}

.form-signup {
	animation: hideSignup .3s ease-out forwards;
}

.form-wrapper .form-signup {
	animation: showSignup .3s ease-in forwards;
}

@keyframes showSignup {
	0% {
		background: #d7e7f1;
		
	}
	50% {
	
	}
	100% {
		background-color: #d7e7f1;
	
	}
}

.form-wrapper.form [type='submit'] {
	opacity: 1;
	transform: translateX(0);
	transition: all .4s ease-in;
}

.form legend {
	position: absolute;
	overflow: hidden;
	width: 1px;
	height: 1px;
	clip: rect(0 0 0 0);
}

.form fieldset {
	position: relative;
	opacity: inherit;
	margin: 0;
	padding: 0;
	border: 0;
	transition: all .3s ease-out;
	display: flex;
    flex-wrap: wrap;
	width: 455px;
	
}

.input-block {
	margin-bottom: 20px;
	margin-left: 20px;
}

.input-block label {
	font-size: 14px;
  color: #a94d19;
}

.input-block input {
	display: block;
	width: 100%;
	margin-top: 8px;
	padding-right: 15px;
	padding-left: 15px;
	font-size: 16px;
	line-height: 40px;
	color: #a94d19;
  background: #f8f7f8;
  border: 1px solid #a94d19;
  border-radius: 2px;
}

.form [type='submit'] {

	display: block;
	min-width: 120px;
	margin: 30px auto 10px;
	font-size: 18px;
	line-height: 40px;
	border-radius: 25px;
	border: none;
	transition: all .3s ease-out;
}

.btn-signup {
	color: #fff;
	background: #a94d19;
	transition: all .3s ease-out;

}


</style>