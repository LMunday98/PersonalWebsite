<template>
  <!-- Wrapper -->
			<div id="wrapper">

				<!-- Main -->
					<section id="main">
						<header>
							<span class="avatar"><img src="../images/avatar.jpg" alt="" /></span>
							<h1>Luke Munday</h1>
							<p>Graduate Software Developer</p>
						</header>
						<hr />
						<a href="#" class="button">Portfolio</a>
						<form method="post" action="#" style="display: none">
							<div class="field">
								<input type="text" name="name" id="name" placeholder="Name" />
							</div>
							<div class="field">
								<input type="email" name="email" id="email" placeholder="Email" />
							</div>
							<div class="field">
								<div class="select-wrapper">
									<select name="department" id="department">
										<option value="">Department</option>
										<option value="sales">Sales</option>
										<option value="tech">Tech Support</option>
										<option value="null">/dev/null</option>
									</select>
								</div>
							</div>
							<div class="field">
								<textarea name="message" id="message" placeholder="Message" rows="4"></textarea>
							</div>
							<div class="field">
								<input type="checkbox" id="human" name="human" /><label for="human">I'm a human</label>
							</div>
							<div class="field">
								<label>But are you a robot?</label>
								<input type="radio" id="robot_yes" name="robot" /><label for="robot_yes">Yes</label>
								<input type="radio" id="robot_no" name="robot" /><label for="robot_no">No</label>
							</div>
							<ul class="actions">
								<li><a href="#" class="button">Get Started</a></li>
							</ul>
						</form>
						<hr />
						<footer>
							<ul class="icons">
								<li><a href="https://github.com/LMunday98" class="fa-github">GitHub</a></li>
								<li><a href="https://www.linkedin.com/in/luke-m-53478a133/" class="fa-linkedin">LinkedIn</a></li>
							</ul>
						</footer>
					</section>

				<!-- Footer -->
					<footer id="footer">
						<ul class="copyright">
							<li>&copy; Luke Munday</li><li>Design: <a href="http://html5up.net">HTML5 UP</a></li>
						</ul>
					</footer>

			</div>
</template>

<script>
export default {
  name: 'LandingPage',
}
</script>

<style scoped>
  @import "../assets/css/landing.css"
</style>