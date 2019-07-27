<template>
    			<footer id="footer" class="bg-color-quaternary border-top-0 mt-0">
				<div class="container">
					<div class="row justify-content-between pt-5 pb-4">
						<div class="col-md-5 col-lg-3 mb-4 mb-lg-0">
							<h2 class="font-weight-semibold text-color-light text-6 mb-3">Contact Details</h2>
							<p>Porto Education 123 <br>Porto Blvd, Suite</p>
							<span class="d-block text-5 mb-2">
								Call: <a href="tel:+1234567890" class="text-3">123-456-7890</a>
							</span>
							<span class="d-block text-5 mb-4">
								Email: <a href="mailto:info@porto.com" class="text-3">info@porto.com</a>
							</span>
							<ul class="social-icons social-icons-transparent">
								<li class="social-icons-facebook"><a href="http://www.facebook.com/" target="_blank" title="Facebook"><i class="fab fa-facebook-f"></i></a></li>
								<li class="social-icons-twitter"><a href="http://www.twitter.com/" target="_blank" title="Twitter"><i class="fab fa-twitter"></i></a></li>
								<li class="social-icons-linkedin"><a href="http://www.linkedin.com/" target="_blank" title="Linkedin"><i class="fab fa-linkedin-in"></i></a></li>
							</ul>
						</div>
						<div class="col-md-7 col-lg-4 mb-4 mb-lg-0">
							<div class="row">
								<div class="col">
									<h2 class="font-weight-semibold text-color-light text-6 mb-3">Courses</h2>
								</div>
							</div>
							<div class="row">
								<div class="col-md-6">
									<ul class="list list-unstyled mb-0">
										<li><a href="demo-education-courses-detail.htm">Archaeology</a></li>
										<li><a href="demo-education-courses-detail.htm">Architecture</a></li>
										<li><a href="demo-education-courses-detail.htm">Art & Design</a></li>
										<li><a href="demo-education-courses-detail.htm">Aural & Oral Sciences</a></li>
										<li><a href="demo-education-courses-detail.htm">Biological Sciences</a></li>
										<li><a href="demo-education-courses-detail.htm">Building</a></li>
									</ul>
								</div>
								<div class="col-md-6">
									<ul class="list list-unstyled mb-0">
										<li><a href="demo-education-courses-detail.htm">Management Studies</a></li>
										<li><a href="demo-education-courses-detail.htm">Celtic Studies</a></li>
										<li><a href="demo-education-courses-detail.htm">Chemical Engineering</a></li>
										<li><a href="demo-education-courses-detail.htm">Chemistry</a></li>
										<li><a href="demo-education-courses-detail.htm">Civil Engineering</a></li>
										<li><a href="demo-education-courses-detail.htm" class="text-color-primary">Much More</a></li>
									</ul>
								</div>
							</div>
						</div>
						<div class="col-lg-4">
							<div class="row">
								<div class="col">
									<h2 class="font-weight-semibold text-color-light text-6 mb-3">Newsletter</h2>
									<div class="newsletter">
										<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse in arcu facilisis quam.</p>

										<div class="alert alert-success d-none" id="newsletterSuccess">
											<strong>Success!</strong> You've been added to our email list.
										</div>

										<div class="alert alert-danger d-none" id="newsletterError"></div>

										<form id="newsletterForm" action="php/newsletter-subscribe.php" method="POST">
											<div class="input-group custom-input-group-style-1">
												<input class="form-control form-control-sm" placeholder="Email Address" name="newsletterEmail" id="newsletterEmail" type="text">
												<span class="input-group-append">
													<button class="btn btn-primary px-4" type="submit">Subscribe</button>
												</span>
											</div>
										</form>
									</div>
								</div>
							</div>
						</div>
					</div>
				</div>
				<div class="footer-copyright bg-color-quaternary border-top-0">
					<div class="container">
						<div class="row">
							<div class="col">
								<p class="text-center">© Copyright 2019. All Rights Reserved.</p>
							</div>
						</div>
					</div>
				</div>
			</footer>
</template>
