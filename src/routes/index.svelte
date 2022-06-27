<script>
import Footer from "../components/Footer.svelte";
import IEpanel from "../components/IEpanel.svelte";
import Nav from "../components/Nav.svelte";
import PreFooter from "../components/PreFooter.svelte";

import Preloader from "../components/Preloader.svelte";

</script>

<svelte:head>
	<title>Classique Brushes::: Home Page</title>
</svelte:head>

<IEpanel />
<Preloader />
<div class="page">
	<!-- Page Header-->
	<header class="section page-header">
		<!-- RD Navbar-->
		<div class="rd-navbar-wrap">
			<Nav/>
		</div>
	</header>
	<!-- Swiper-->
	<section
		class="section swiper-container swiper-slider swiper-slider-3 context-dark"
		data-loop="true"
		data-autoplay="4200"
		data-simulate-touch="false"
		data-slide-effect="fade"
	>
		<div class="swiper-wrapper">
			<div
				class="swiper-slide"
				data-slide-bg="images/slide-05.jpeg"
				style="background-position: center;"
			>
				<div class="swiper-slide-caption section-xl">
					<div class="container">
						<div class="row">
							<div class="col-xs-9 col-sm-6 col-lg-3">
								<div
									class="swiper-count"
									data-caption-animate="fadeInUp"
									data-caption-delay="100"
								>
									<span>01</span>
								</div>
								<div
									class="divider divider-xl"
									data-caption-animate="fadeInUp"
									data-caption-delay="350"
								/>
								<h2
									class="font-weight-light"
									data-caption-animate="fadeInUp"
									data-caption-delay="450"
								>
									Quality Beauty Treatments
								</h2>
							</div>
						</div>
						<div class="row justify-content-sm-end">
							<div class="col-xs-9 col-sm-7 col-md-5">
								<div class="block-xs-max">
									<div
										class="heading-1"
										data-caption-animate="fadeInUp"
										data-caption-delay="100"
									>
										<span
											>Experience the Best Beauty Services</span
										>
									</div>
									<p
										data-caption-animate="fadeInUp"
										data-caption-delay="350"
									>
										at an award-winning salon
									</p>
									<a
										class="button button-white-outline"
										href="#"
										data-caption-animate="fadeInUp"
										data-caption-delay="450">Book now</a
									>
								</div>
							</div>
						</div>
					</div>
				</div>
			</div>
			<div
				class="swiper-slide"
				data-slide-bg="images/slide-06.jpeg"
				style="background-position: center;"
			>
				<div class="swiper-slide-caption section-xl">
					<div class="container">
						<div class="row">
							<div class="col-xs-9 col-sm-6 col-lg-3">
								<div
									class="swiper-count"
									data-caption-animate="fadeInUp"
									data-caption-delay="100"
								>
									<span>02</span>
								</div>
								<div
									class="divider divider-xl"
									data-caption-animate="fadeInUp"
									data-caption-delay="350"
								/>
								<h2
									class="font-weight-light"
									data-caption-animate="fadeInUp"
									data-caption-delay="450"
								>
									Beauty Care for Everyone
								</h2>
							</div>
						</div>
						<div class="row justify-content-sm-end">
							<div class="col-xs-9 col-sm-7 col-md-5">
								<div class="block-xs-max">
									<div
										class="heading-1"
										data-caption-animate="fadeInUp"
										data-caption-delay="100"
									>
										<span>Professional Spa & Skin Care</span
										>
									</div>
									<p
										data-caption-animate="fadeInUp"
										data-caption-delay="350"
									>
										for all clients of Classiquebrushes
									</p>
									<a
										class="button button-white-outline"
										href="#"
										data-caption-animate="fadeInUp"
										data-caption-delay="450">Book now</a
									>
								</div>
							</div>
						</div>
					</div>
				</div>
			</div>
			<div
				class="swiper-slide"
				data-slide-bg="images/slide-07.jpeg"
				style="background-position: center;"
			>
				<div class="swiper-slide-caption section-xl">
					<div class="container">
						<div class="row">
							<div class="col-xs-9 col-sm-6 col-lg-3">
								<div
									class="swiper-count"
									data-caption-animate="fadeInUp"
									data-caption-delay="100"
								>
									<span>03</span>
								</div>
								<div
									class="divider divider-xl"
									data-caption-animate="fadeInUp"
									data-caption-delay="350"
								/>
								<h2
									class="font-weight-light"
									data-caption-animate="fadeInUp"
									data-caption-delay="450"
								>
									Entrust Your Beauty to Professionals
								</h2>
							</div>
						</div>
						<div class="row justify-content-sm-end">
							<div class="col-xs-9 col-sm-7 col-md-5">
								<div class="block-xs-max">
									<div
										class="heading-1"
										data-caption-animate="fadeInUp"
										data-caption-delay="100"
									>
										<span
											>Qualified Team of Estheticians</span
										>
									</div>
									<p
										data-caption-animate="fadeInUp"
										data-caption-delay="350"
									>
										always ready to help you
									</p>
									<a
										class="button button-white-outline"
										href="#"
										data-caption-animate="fadeInUp"
										data-caption-delay="450">Book now</a
									>
								</div>
							</div>
						</div>
					</div>
				</div>
			</div>
		</div>
	</section>
	<!-- About Us-->
	<section class="section section-lg bg-default">
		<div class="container">
			<div class="row row-30">
				<div
					class="col-xs-6 col-lg-3 wow fadeInSmall"
					data-wow-delay=".1s"
				>
					<div class="features-box">
						<div class="features-box-image">
							<svg
								width="70"
								height="80"
								viewBox="0 0 70 80"
								fill="none"
								xmlns="https://www.w3.org/2000/svg"
							>
								<path
									d="M63.6786 60.3686L63.3944 60.288C62.4632 60.0389 61.6695 59.7898 60.9785 59.5506C62.9238 48.4058 69.3923 0 35.0013 0C0.605299 0 7.07384 48.4058 9.01927 59.5508C8.32835 59.79 7.53691 60.0391 6.60576 60.2881L6.3191 60.3687C2.54084 61.6139 1.33996e-07 65.105 1.33996e-07 69.0455V80H35.0012H70V69.0455C70 65.105 67.4568 61.6138 63.6786 60.3686ZM55.9922 57.4097C49.4379 54.9219 47.7325 53.1275 47.2964 52.2803C47.2817 52.2509 47.2669 52.2169 47.2524 52.1875L47.2401 50.2148C52.3733 45.1514 56.5705 37.6758 56.5705 29.8498C56.5705 29.4445 56.5631 29.0442 56.5461 28.6462L58.9153 30.26C59.3074 33.6987 59.4642 37.4244 59.3883 41.3964C59.2511 48.4716 58.3911 54.7363 57.8128 58.2202C57.1757 57.9175 56.6072 57.6416 55.9922 57.4097ZM23.652 46.2964C19.712 41.8237 17.2888 36.5112 16.8502 31.4856C22.0348 29.2639 28.2486 25.5677 35.4301 20.4223C36.9369 19.342 38.3899 18.2666 39.7595 17.2278L52.9637 26.2097C53.1352 27.3864 53.2259 28.6011 53.2259 29.8498C53.2259 35.3394 50.7193 41.3342 46.3505 46.2964C44.4296 48.4766 42.2783 50.3028 40.1269 51.5723C38.206 52.71 36.3879 53.335 35.001 53.335C33.6142 53.335 31.7912 52.71 29.8751 51.5723C27.7243 50.3028 25.5729 48.4766 23.652 46.2964ZM58.0333 24.6984C58.1068 25.05 58.1779 25.4077 58.244 25.7666L42.5431 15.0842C46.4438 12.0277 49.3057 9.58375 50.2196 8.79516C50.8346 9.38109 51.4178 10.0122 51.969 10.6897C54.7672 14.1358 56.8081 18.8489 58.0333 24.6984ZM18.0263 10.6958C19.9106 8.37281 22.1867 6.58078 24.7914 5.36984C27.6998 4.01859 31.1349 3.33375 35.0013 3.33375C38.8629 3.33375 42.298 4.01859 45.2039 5.36859C46.0223 5.74828 46.8087 6.18531 47.561 6.67844C45.6033 8.35203 40.0634 12.998 33.4526 17.7319C24.2938 24.2919 16.654 28.4802 11.1141 30.0023C11.3272 28.1712 11.6067 26.422 11.9545 24.7619C13.1773 18.8867 15.2208 14.1553 18.0263 10.6958ZM10.6144 41.5148C10.5581 38.7231 10.6169 36.0534 10.7883 33.5192C11.6851 33.3191 12.6308 33.053 13.6183 32.7233C14.4833 39.4811 18.2614 45.7737 22.76 50.2098L22.7454 52.1875C22.7307 52.2169 22.721 52.2509 22.7062 52.2803C22.2701 53.1275 20.5648 54.9219 14.008 57.4097C13.3904 57.6416 12.8245 57.9175 12.1875 58.2227C11.6117 54.7631 10.759 48.5595 10.6144 41.5148ZM66.6531 76.665H35.0013H3.34467V69.0453C3.34467 66.56 4.93977 64.3603 7.31894 63.5522L7.50524 63.4961C10.6318 62.6587 12.3591 61.8359 13.7483 61.1719C14.2849 60.918 14.748 60.6934 15.1988 60.5225C18.9427 59.1016 24.1028 56.8603 25.6783 53.8062C25.7396 53.6891 25.7837 53.5889 25.8082 53.5303L26.0385 53.0225C29.1453 55.3175 32.3429 56.665 35.0013 56.665C37.6574 56.665 40.8549 55.3173 43.9641 53.0225L44.1945 53.5303C44.2141 53.5841 44.2582 53.6866 44.3195 53.8013C45.8925 56.8555 51.0551 59.1016 54.8039 60.5248C55.2522 60.6933 55.7153 60.918 56.2519 61.1719C57.6411 61.8359 59.366 62.6587 62.4974 63.4961L62.6837 63.5498C65.0604 64.3605 66.653 66.5602 66.653 69.0455V76.665H66.6531Z"
									fill="url(#svg-1)"
								/>
								<defs>
									<lineargradient
										id="svg-1"
										x1="35"
										y1="0"
										x2="35"
										y2="80"
										gradientUnits="userSpaceOnUse"
									>
										<stop offset="0" stop-color="#7093D4" />
										<stop offset="1" stop-color="#DD87A5" />
									</lineargradient>
								</defs>
							</svg>
						</div>
						<h4 class="features-box-title">Professional Team</h4>
						<div class="features-box-decor">
							<div class="features-box-decor-item" />
							<div class="features-box-decor-item" />
							<div class="features-box-decor-item" />
						</div>
						<p>
							We employ the team of the most qualified
							estheticians, hair stylists, nail artists etc.
						</p>
					</div>
				</div>
				<div
					class="col-xs-6 col-lg-3 wow fadeInSmall"
					data-wow-delay=".2s"
				>
					<div class="features-box">
						<div class="features-box-image">
							<svg
								width="80"
								height="80"
								viewBox="0 0 80 80"
								fill="none"
								xmlns="https://www.w3.org/2000/svg"
							>
								<path
									d="M80 32.5301V32.539L79.9911 39.0858L76.6409 68.1972V75.6755C76.6409 78.0604 74.7004 80 72.3164 80H59.8373H54.128H39.4702H31.1627H4.32444C1.94044 80.0009 0 78.0604 0 75.6764V65.3678V54.2913C0 51.8984 1.94044 49.9668 4.32444 49.9668H29.624V37.9409C29.624 35.5391 30 33.1719 30.7182 30.915C31.4364 28.6412 32.5049 26.4963 33.8889 24.5389C36.2907 21.1282 37.5813 17.0775 37.5813 12.9059V8.64987V4.32449C37.5813 1.93158 39.5129 0 41.9058 0H49.0853C51.4782 0 53.4187 1.93158 53.4187 4.32449V8.64898V12.905C53.4187 14.9904 53.7431 17.042 54.3591 19.0073C54.9831 20.9647 55.9058 22.8278 57.1111 24.5292L57.12 24.538C57.9316 25.7007 58.6418 26.923 59.2222 28.2048H60.5982H66.504H72.4098H75.6747C78.0418 28.2048 79.9653 30.1026 79.9991 32.4608V32.5035V32.5301H80ZM43.7947 63.83V65.3687V75.6764C43.7947 76.112 43.7351 76.5315 43.6062 76.9244H49.9911C49.8631 76.5315 49.8027 76.1128 49.8027 75.6764V68.1981C49.7938 68.1723 49.7938 68.1385 49.7938 68.1128L46.4267 39.0955V32.531C46.4267 30.1381 48.3582 28.2065 50.7511 28.2065H54.6996H55.7849C55.4258 27.5656 55.0329 26.9327 54.6053 26.3176C53.2124 24.3514 52.144 22.1976 51.4258 19.9416C50.7164 17.6766 50.3404 15.3086 50.3404 12.9077V10.1894H40.6578V12.9077C40.6578 17.7113 39.1707 22.3949 36.4018 26.3096C35.1964 28.019 34.2649 29.8821 33.6498 31.8484C33.0258 33.8057 32.7013 35.8573 32.7013 37.9426V49.9686H39.4702C41.8551 49.9686 43.7947 51.9001 43.7947 54.293V63.83ZM76.9227 32.539V32.5301V32.5212C76.9138 31.8288 76.3671 31.2821 75.6747 31.2821H73.9484V36.4449C73.9484 37.2911 73.256 37.9835 72.4098 37.9835C71.5547 37.9835 70.8711 37.2911 70.8711 36.4449V31.2821H68.0418V36.4449C68.0418 37.2911 67.3493 37.9835 66.5031 37.9835C65.6569 37.9835 64.9644 37.2911 64.9644 36.4449V31.2821H62.1351V36.4449C62.1351 37.2911 61.4516 37.9835 60.5964 37.9835C59.7502 37.9835 59.0578 37.2911 59.0578 36.4449V31.2821H58.2133H56.2391V36.4449C56.2391 37.2911 55.5467 37.9835 54.7004 37.9835C53.8453 37.9835 53.1618 37.2911 53.1618 36.4449V31.2821H50.7511C50.0587 31.2821 49.5031 31.8377 49.5031 32.5301V38.9151L52.7084 66.5732H73.7253L76.9138 38.9062L76.9227 32.539ZM73.5644 75.6764V69.6506H52.88V75.6764C52.88 76.36 53.4356 76.9244 54.128 76.9244H59.8373H72.3156C73 76.9235 73.5644 76.36 73.5644 75.6764ZM50.3422 7.11119V4.32449C50.3422 3.97427 50.2053 3.67471 49.9751 3.44448C49.744 3.21337 49.4364 3.07737 49.0862 3.07737H41.9067C41.2142 3.07737 40.6587 3.63293 40.6587 4.32538V7.11119H50.3422ZM40.7182 75.6764V65.3678H3.07733V75.6755C3.08622 76.3591 3.64178 76.9235 4.32533 76.9235H31.1627H39.4702C40.1538 76.9235 40.7182 76.36 40.7182 75.6764ZM40.7182 62.2914V54.2913C40.7182 53.5988 40.1538 53.0433 39.4702 53.0433H4.32444C3.64089 53.0433 3.08533 53.5988 3.07644 54.2913V62.2914H40.7182Z"
									fill="url(#svg-1)"
								/>
							</svg>
						</div>
						<h4 class="features-box-title">Premium Products</h4>
						<div class="features-box-decor">
							<div class="features-box-decor-item" />
							<div class="features-box-decor-item" />
							<div class="features-box-decor-item" />
						</div>
						<p>
							At Classiquebrushes, we use only the best skin care and
							beauty products for our clients.
						</p>
					</div>
				</div>
				<div
					class="col-xs-6 col-lg-3 wow fadeInSmall"
					data-wow-delay=".3s"
				>
					<div class="features-box">
						<div class="features-box-image">
							<svg
								width="73"
								height="80"
								viewBox="0 0 73 80"
								fill="none"
								xmlns="https://www.w3.org/2000/svg"
							>
								<path
									fill-rule="evenodd"
									clip-rule="evenodd"
									d="M1.68268 45.0031C1.46283 45 1.24456 45.0408 1.04055 45.1231C0.836544 45.2055 0.650862 45.3277 0.494298 45.4828C0.337734 45.6379 0.213411 45.8227 0.128555 46.0264C0.043698 46.2302 4.03695e-08 46.4489 4.03695e-08 46.6697C4.03695e-08 46.8906 0.043698 47.1093 0.128555 47.313C0.213411 47.5168 0.337734 47.7016 0.494298 47.8567C0.650862 48.0117 0.836544 48.134 1.04055 48.2164C1.24456 48.2987 1.46283 48.3395 1.68268 48.3364H13.2507C13.4705 48.3395 13.6888 48.2987 13.8928 48.2164C14.0968 48.134 14.2825 48.0117 14.439 47.8567C14.5956 47.7016 14.7199 47.5168 14.8048 47.313C14.8896 47.1093 14.9333 46.8906 14.9333 46.6697C14.9333 46.4489 14.8896 46.2302 14.8048 46.0264C14.7199 45.8227 14.5956 45.6379 14.439 45.4828C14.2825 45.3277 14.0968 45.2055 13.8928 45.1231C13.6888 45.0408 13.4705 45 13.2507 45.0031H1.68268Z"
									fill="url(#paint0_linear)"
								/>
								<path
									fill-rule="evenodd"
									clip-rule="evenodd"
									d="M59.7494 56.6664C59.5295 56.6632 59.3113 56.704 59.1073 56.7864C58.9033 56.8688 58.7176 56.991 58.561 57.1461C58.4044 57.3012 58.2801 57.486 58.1953 57.6897C58.1104 57.8935 58.0667 58.1121 58.0667 58.333C58.0667 58.5539 58.1104 58.7726 58.1953 58.9763C58.2801 59.1801 58.4044 59.3649 58.561 59.5199C58.7176 59.675 58.9033 59.7973 59.1073 59.8796C59.3113 59.962 59.5295 60.0028 59.7494 59.9997H71.3174C71.5372 60.0028 71.7555 59.962 71.9595 59.8796C72.1635 59.7973 72.3492 59.675 72.5057 59.5199C72.6623 59.3649 72.7866 59.1801 72.8715 58.9763C72.9563 58.7726 73 58.5539 73 58.333C73 58.1121 72.9563 57.8935 72.8715 57.6897C72.7866 57.486 72.6623 57.3012 72.5057 57.1461C72.3492 56.991 72.1635 56.8688 71.9595 56.7864C71.7555 56.704 71.5372 56.6632 71.3174 56.6664H59.7494Z"
									fill="url(#paint1_linear)"
								/>
								<path
									d="M19.9095 33.3363C19.6168 33.336 19.3292 33.4136 19.076 33.5611C18.8227 33.7086 18.6128 33.9208 18.4676 34.1761L11.8314 45.8427C11.6882 46.0945 11.6129 46.3795 11.6129 46.6695C11.6129 46.9595 11.6882 47.2445 11.8314 47.4963L18.4676 59.1629C18.6128 59.4182 18.8227 59.6304 19.076 59.7779C19.3292 59.9254 19.6168 60.003 19.9095 60.0027H33.1819C33.4741 60.0024 33.761 59.9246 34.0136 59.7771C34.2663 59.6297 34.4757 59.4178 34.6206 59.1629L41.2568 47.4963C41.4005 47.2448 41.4764 46.9599 41.477 46.6699C41.4776 46.3799 41.4028 46.0948 41.2601 45.8427L34.6239 34.1761C34.4787 33.9208 34.2688 33.7086 34.0155 33.5611C33.7623 33.4136 33.4747 33.336 33.1819 33.3363H19.9095ZM20.8719 36.6696H32.2195L37.9063 46.6695L32.2163 56.6694H20.8719L15.1851 46.6695L20.8719 36.6696Z"
									fill="url(#paint2_linear)"
								/>
								<path
									d="M39.8181 45.0029C39.5254 45.0027 39.2378 45.0802 38.9845 45.2277C38.7313 45.3752 38.5214 45.5874 38.3761 45.8428L31.74 57.5093C31.5967 57.7611 31.5214 58.0461 31.5214 58.3361C31.5214 58.6262 31.5967 58.9111 31.74 59.163L38.3761 70.8295C38.5214 71.0849 38.7313 71.2971 38.9845 71.4446C39.2378 71.5921 39.5254 71.6696 39.8181 71.6694H53.0905C53.3832 71.6696 53.6708 71.5921 53.924 71.4446C54.1773 71.2971 54.3872 71.0849 54.5324 70.8295L61.1686 59.1597C61.3113 58.9076 61.3861 58.6225 61.3855 58.3325C61.3849 58.0425 61.309 57.7576 61.1653 57.5061L54.5291 45.8428C54.3842 45.5879 54.1748 45.376 53.9222 45.2285C53.6696 45.0811 53.3827 45.0033 53.0905 45.0029H39.8181ZM40.7805 48.3362H52.1281L57.8149 58.3329L52.1249 68.3361H40.7805L35.0937 58.3361L40.7805 48.3362Z"
									fill="url(#paint3_linear)"
								/>
								<path
									d="M19.9095 10.0032C19.6168 10.0029 19.3292 10.0805 19.076 10.228C18.8227 10.3755 18.6128 10.5877 18.4676 10.843L11.8314 22.5096C11.6882 22.7614 11.6129 23.0464 11.6129 23.3364C11.6129 23.6264 11.6882 23.9114 11.8314 24.1632L18.4676 35.8298C18.6128 36.0851 18.8227 36.2973 19.076 36.4448C19.3292 36.5923 19.6168 36.6699 19.9095 36.6696H33.1819C33.4746 36.6699 33.7622 36.5923 34.0155 36.4448C34.2687 36.2973 34.4786 36.0851 34.6239 35.8298L41.2601 24.1632C41.4033 23.9114 41.4786 23.6264 41.4786 23.3364C41.4786 23.0464 41.4033 22.7614 41.2601 22.5096L34.6239 10.843C34.4786 10.5877 34.2687 10.3755 34.0155 10.228C33.7622 10.0805 33.4746 10.0029 33.1819 10.0032H19.9095ZM20.8719 13.3365H32.2195L37.9063 23.3364L32.2163 33.3363H20.8719L15.1851 23.3364L20.8719 13.3365Z"
									fill="url(#paint4_linear)"
								/>
								<path
									d="M39.8181 21.6698C39.5254 21.6695 39.2378 21.7471 38.9845 21.8946C38.7313 22.0421 38.5214 22.2543 38.3761 22.5096L31.74 34.1762C31.5967 34.428 31.5214 34.713 31.5214 35.003C31.5214 35.293 31.5967 35.578 31.74 35.8298L38.3761 47.4964C38.5214 47.7517 38.7313 47.9639 38.9845 48.1114C39.2378 48.2589 39.5254 48.3365 39.8181 48.3362H53.0905C53.3832 48.3365 53.6708 48.2589 53.924 48.1114C54.1773 47.9639 54.3872 47.7517 54.5324 47.4964L61.1686 35.8298C61.3118 35.578 61.3872 35.293 61.3872 35.003C61.3872 34.713 61.3118 34.428 61.1686 34.1762L54.5324 22.5096C54.3872 22.2543 54.1773 22.0421 53.924 21.8946C53.6708 21.7471 53.3832 21.6695 53.0905 21.6698H39.8181ZM40.7805 25.0031H52.1281L57.8149 35.003L52.1249 45.0029H40.7805L35.0937 35.003L40.7805 25.0031Z"
									fill="url(#paint5_linear)"
								/>
								<path
									fill-rule="evenodd"
									clip-rule="evenodd"
									d="M39.8602 68.3363C39.5627 68.3283 39.2686 68.401 39.0086 68.5464C38.7487 68.6919 38.5324 68.9048 38.3826 69.1631L33.4313 77.4573C33.3159 77.645 33.2387 77.854 33.2042 78.0719C33.1698 78.2899 33.1788 78.5124 33.2307 78.7268C33.2825 78.9413 33.3763 79.1433 33.5065 79.3211C33.6367 79.4988 33.8007 79.6488 33.989 79.7624C34.1774 79.8759 34.3863 79.9509 34.6037 79.9827C34.8211 80.0145 35.0426 80.0026 35.2554 79.9477C35.4681 79.8929 35.668 79.7961 35.8432 79.6631C36.0185 79.53 36.1657 79.3634 36.2764 79.1728L41.2276 70.8786C41.3809 70.6293 41.4661 70.3439 41.4745 70.0509C41.483 69.758 41.4145 69.4679 41.2758 69.2101C41.1371 68.9523 40.9332 68.7359 40.6847 68.5824C40.4362 68.429 40.1518 68.3441 39.8602 68.3363Z"
									fill="url(#paint6_linear)"
								/>
								<path
									fill-rule="evenodd"
									clip-rule="evenodd"
									d="M61.3502 11.6698C61.1092 11.6747 60.8722 11.7323 60.6556 11.8386C60.4391 11.9448 60.2482 12.0971 60.0962 12.2849L51.8301 22.2491C51.6903 22.4172 51.585 22.6114 51.52 22.8205C51.455 23.0297 51.4316 23.2496 51.4513 23.4678C51.4709 23.686 51.5332 23.8982 51.6345 24.0922C51.7358 24.2862 51.8741 24.4582 52.0416 24.5985C52.2091 24.7388 52.4025 24.8445 52.6107 24.9097C52.8189 24.9748 53.0379 24.9982 53.255 24.9783C53.4722 24.9585 53.6834 24.8958 53.8764 24.7939C54.0695 24.692 54.2407 24.5529 54.3802 24.3846L62.6463 14.4204C62.8547 14.176 62.9881 13.8762 63.0306 13.5573C63.0731 13.2384 63.0228 12.9139 62.8857 12.6231C62.7487 12.3322 62.5308 12.0875 62.2583 11.9183C61.9858 11.7492 61.6704 11.6628 61.3502 11.6698Z"
									fill="url(#paint7_linear)"
								/>
								<path
									fill-rule="evenodd"
									clip-rule="evenodd"
									d="M13.2669 -3.16507e-05C12.9647 0.000766178 12.6684 0.0845647 12.41 0.242174C12.1517 0.399784 11.9411 0.625271 11.801 0.89433C11.6609 1.16339 11.5967 1.46579 11.6152 1.76886C11.6337 2.07192 11.7342 2.36413 11.906 2.61398L18.5162 12.5716C18.6355 12.7573 18.7903 12.9174 18.9717 13.0425C19.1531 13.1675 19.3575 13.255 19.5729 13.3C19.7883 13.345 20.0104 13.3466 20.2264 13.3045C20.4424 13.2624 20.6479 13.1776 20.831 13.055C21.014 12.9324 21.171 12.7744 21.2927 12.5903C21.4145 12.4062 21.4985 12.1997 21.54 11.9826C21.5815 11.7656 21.5797 11.5424 21.5345 11.3261C21.4893 11.1098 21.4018 10.9046 21.277 10.7225L14.6667 0.765038C14.5161 0.529757 14.3089 0.336294 14.0642 0.202603C13.8196 0.0689131 13.5454 -0.000778873 13.2669 -3.16507e-05Z"
									fill="url(#paint8_linear)"
								/>
								<defs>
									<lineargradient
										id="paint0_linear"
										x1="7.46667"
										y1="45.0029"
										x2="7.46667"
										y2="48.3366"
										gradientUnits="userSpaceOnUse"
									>
										<stop offset="0" stop-color="#7093D4" />
										<stop offset="1" stop-color="#DD87A5" />
									</lineargradient>
									<lineargradient
										id="paint1_linear"
										x1="65.5334"
										y1="56.6661"
										x2="65.5334"
										y2="59.9998"
										gradientUnits="userSpaceOnUse"
									>
										<stop offset="0" stop-color="#7093D4" />
										<stop offset="1" stop-color="#DD87A5" />
									</lineargradient>
									<lineargradient
										id="paint2_linear"
										x1="26.5449"
										y1="33.3363"
										x2="26.5449"
										y2="60.0028"
										gradientUnits="userSpaceOnUse"
									>
										<stop offset="0" stop-color="#7093D4" />
										<stop offset="1" stop-color="#DD87A5" />
									</lineargradient>
									<lineargradient
										id="paint3_linear"
										x1="46.4535"
										y1="45.0029"
										x2="46.4535"
										y2="71.6694"
										gradientUnits="userSpaceOnUse"
									>
										<stop offset="0" stop-color="#7093D4" />
										<stop offset="1" stop-color="#DD87A5" />
									</lineargradient>
									<lineargradient
										id="paint4_linear"
										x1="26.5457"
										y1="10.0032"
										x2="26.5457"
										y2="36.6696"
										gradientUnits="userSpaceOnUse"
									>
										<stop offset="0" stop-color="#7093D4" />
										<stop offset="1" stop-color="#DD87A5" />
									</lineargradient>
									<lineargradient
										id="paint5_linear"
										x1="46.4543"
										y1="21.6698"
										x2="46.4543"
										y2="48.3363"
										gradientUnits="userSpaceOnUse"
									>
										<stop offset="0" stop-color="#7093D4" />
										<stop offset="1" stop-color="#DD87A5" />
									</lineargradient>
									<lineargradient
										id="paint6_linear"
										x1="37.3295"
										y1="68.3357"
										x2="37.3295"
										y2="80"
										gradientUnits="userSpaceOnUse"
									>
										<stop offset="0" stop-color="#7093D4" />
										<stop offset="1" stop-color="#DD87A5" />
									</lineargradient>
									<lineargradient
										id="paint7_linear"
										x1="57.2449"
										y1="11.6694"
										x2="57.2449"
										y2="24.9852"
										gradientUnits="userSpaceOnUse"
									>
										<stop offset="0" stop-color="#7093D4" />
										<stop offset="1" stop-color="#DD87A5" />
									</lineargradient>
									<lineargradient
										id="paint8_linear"
										x1="16.5909"
										y1="0"
										x2="16.5909"
										y2="13.335"
										gradientUnits="userSpaceOnUse"
									>
										<stop offset="0" stop-color="#7093D4" />
										<stop offset="1" stop-color="#DD87A5" />
									</lineargradient>
								</defs>
							</svg>
						</div>
						<h4 class="features-box-title">Medical Education</h4>
						<div class="features-box-decor">
							<div class="features-box-decor-item" />
							<div class="features-box-decor-item" />
							<div class="features-box-decor-item" />
						</div>
						<p>
							All our team members have higher medical education
							in beauty therapy.
						</p>
					</div>
				</div>
				<div
					class="col-xs-6 col-lg-3 wow fadeInSmall"
					data-wow-delay=".4s"
				>
					<div class="features-box">
						<div class="features-box-image">
							<svg
								width="99"
								height="80"
								viewBox="0 0 99 80"
								fill="none"
								xmlns="https://www.w3.org/2000/svg"
							>
								<path
									d="M95.9978 53.9978C95.5613 53.2269 94.6176 52.9049 93.7969 53.2548L86.2794 56.4791C85.8522 56.6628 85.5156 57.0105 85.3449 57.4442C85.1743 57.8779 85.1836 58.3615 85.3716 58.7871L86.8958 62.2358L83.0779 63.8473C80.5914 58.2151 74.7919 54.5152 71.4278 52.756C74.0629 50.3201 77.2169 46.6935 76.2592 43.9681C75.6672 42.2856 73.9062 41.431 71.025 41.431C69.2257 41.431 67.5518 41.4426 65.9627 41.4705V34.536H80.0295C80.9907 34.536 81.7708 33.7546 81.7708 32.7919C81.7708 31.8292 80.9907 31.0478 80.0295 31.0478H22.6756L20.6116 24.6807C23.0308 24.2668 26.3565 23.2773 27.3595 20.9297C27.7936 19.9123 27.962 18.274 26.2915 16.2486C24.4737 14.0463 24.505 13.5998 24.5816 12.5173C24.6734 11.2151 24.7999 9.43145 23.3964 5.68629C22.4237 3.08875 20.8415 1.35046 18.6928 0.519107C15.1825 -0.836639 11.4736 0.86095 10.928 1.12838L1.07033 5.25259C0.241507 5.59908 -0.187997 6.52113 0.0789919 7.38039L14.4836 53.7083C14.71 54.4373 15.3844 54.9338 16.1471 54.9338H26.1406V59.7592C26.1406 60.7219 26.9207 61.5033 27.8819 61.5033H36.4963V71.026C29.1843 72.0248 23.2084 74.3735 23.2084 78.2559C23.2084 79.2186 23.9885 80 24.9496 80H65.3323C66.2935 80 67.0736 79.2186 67.0736 78.2559C67.0736 74.3735 61.0965 72.0248 53.7833 71.026V61.5033H62.3978C63.3589 61.5033 64.139 60.7219 64.139 59.7592V54.9338H67.9128C69.5635 55.6477 78.4346 59.7719 80.3975 66.6449C80.5345 67.1251 80.87 67.5227 81.3192 67.7378C81.5572 67.8529 81.8149 67.9087 82.0714 67.9087C82.3013 67.9087 82.5311 67.8634 82.747 67.7716L97.9341 61.3661C98.3926 61.1719 98.7466 60.7917 98.9068 60.3208C99.067 59.8498 99.0194 59.3313 98.7733 58.8976L95.9978 53.9978ZM71.0262 44.9204C72.2555 44.9204 72.779 45.1041 72.9624 45.1948C72.8603 46.247 70.4121 49.1167 67.6412 51.4445H65.9638V44.9622C67.5112 44.9343 69.1828 44.9204 71.0262 44.9204ZM62.3966 51.4456H29.1634L27.2759 45.3599C31.232 45.9796 38.5835 46.9935 44.2924 46.9935C46.3111 46.9935 47.9885 46.8633 49.277 46.604C53.6278 45.732 57.3633 45.2715 62.4802 45.0634V51.4456H62.3966ZM62.4814 34.5383V41.5729C57.621 41.7705 53.4095 42.2193 48.5956 43.1844C47.53 43.3983 46.0836 43.5053 44.2936 43.5053C37.9183 43.5053 29.0775 42.1287 26.107 41.6357L23.8062 34.5383H62.4814ZM17.4565 3.78173C18.6452 4.24799 19.5228 5.27236 20.138 6.91413C21.2745 9.94654 21.1816 11.2372 21.1096 12.2732C20.968 14.2603 21.1688 15.5195 23.6077 18.4729C24.0941 19.0635 24.2044 19.453 24.1591 19.56C23.8793 20.2146 21.7968 20.9669 19.5205 21.3146L13.8336 3.77127C14.8319 3.49454 16.2086 3.29455 17.4565 3.78173ZM17.4275 51.4456L3.87488 7.85944L10.5856 5.0526L23.112 43.6937L25.5161 51.4445H17.4275V51.4456ZM28.9719 76.5118C31.824 75.2572 37.3008 73.9503 45.1398 73.9503C52.9789 73.9503 58.4568 75.2572 61.3089 76.5118H28.9719ZM50.2997 70.6586C48.5921 70.5284 46.8555 70.4621 45.1398 70.4621C43.4241 70.4621 41.6852 70.5284 39.9788 70.6586V61.5033H50.3008V70.6586H50.2997ZM60.6554 58.0151H52.0409H38.2376H29.6231V54.9338H60.6554V58.0151ZM90.1055 60.8824L89.2708 58.9918L93.7365 57.0767L94.7766 58.9138L90.1055 60.8824Z"
									fill="url(#scg-3)"
								/>
								<defs>
									<lineargradient
										id="scg-3"
										x1="49.5"
										y1="0"
										x2="49.5"
										y2="80"
										gradientUnits="userSpaceOnUse"
									>
										<stop offset="0" stop-color="#7093D4" />
										<stop offset="1" stop-color="#DD87A5" />
									</lineargradient>
								</defs>
							</svg>
						</div>
						<h4 class="features-box-title">The Latest Equipment</h4>
						<div class="features-box-decor">
							<div class="features-box-decor-item" />
							<div class="features-box-decor-item" />
							<div class="features-box-decor-item" />
						</div>
						<p>
							Our salon uses the top-notch equipment for the
							beauty services we provide.
						</p>
					</div>
				</div>
			</div>
		</div>
	</section>
	<!-- Services we offer-->
	<section class="parallax-container" data-parallax-img="images/bg-01.jpeg">
		<div class="parallax-content section-lg">
			<div class="container text-center">
				<div class="row justify-content-xs-center">
					<div class="col-xs-10 col-sm-10 col-md-8 col-lg-6">
						<h1
							class="font-weight-bold wow fadeInSmall"
							data-wow-delay=".1s"
						>
							Our Services
						</h1>
						<div
							class="divider wow fadeInSmall"
							data-wow-delay=".2s"
						/>
						<p class="wow fadeInSmall" data-wow-delay=".3s">
							Treat yourself to one of our signature services. Our
							beauty experts will make you look more beautiful and
							feel better than ever before.
						</p>
					</div>
				</div>
				<div class="row row-30">
					<div
						class="col-sm-6 col-lg-3 wow fadeInSmall"
						data-wow-delay=".1s"
					>
						<article class="services-box">
							<div class="services-box-image">
								<a href="services.html"
									><img
										src="images/services-01-420x526.jpeg"
										alt=""
										width="420"
										height="526"
									/></a
								>
							</div>
							<h4><a href="services.html">Body Treatment</a></h4>
							<p>Invigorating relaxation</p>
						</article>
					</div>
					<div
						class="col-sm-6 col-lg-3 wow fadeInSmall"
						data-wow-delay=".2s"
					>
						<article class="services-box">
							<div class="services-box-image">
								<a href="services.html"
									><img
										src="images/services-02-420x526.jpeg"
										alt=""
										width="420"
										height="526"
									/></a
								>
							</div>
							<h4><a href="services.html">Skin Care</a></h4>
							<p>Facials and skin treatments</p>
						</article>
					</div>
					<div
						class="col-sm-6 col-lg-3 wow fadeInSmall"
						data-wow-delay=".3s"
					>
						<article class="services-box">
							<div class="services-box-image">
								<a href="services.html"
									><img
										src="images/services-03-420x526.jpeg"
										alt=""
										width="420"
										height="526"
									/></a
								>
							</div>
							<h4><a href="services.html">Hair Styling</a></h4>
							<p>Creating the best haircuts</p>
						</article>
					</div>
					<div
						class="col-sm-6 col-lg-3 wow fadeInSmall"
						data-wow-delay=".4s"
					>
						<article class="services-box">
							<div class="services-box-image">
								<a href="services.html"
									><img
										src="images/services-04-420x526.jpeg"
										alt=""
										width="420"
										height="526"
									/></a
								>
							</div>
							<h4><a href="services.html">Pedicure</a></h4>
							<p>Restore your nails’ proper condition</p>
						</article>
					</div>
				</div>
			</div>
		</div>
	</section>
	<!-- You will like to look like goddess every day!-->
	<section class="section section-lg bg-default section-decor">
		<div class="container">
			<div class="row row-30 flex-lg-row-reverse">
				<div class="col-lg-7 wow fadeInSmall" data-wow-delay=".3s">
					<div class="video" data-lightgallery="group">
						<img
							src="images/video-preview-680x398.jpeg"
							alt=""
							width="680"
							height="398"
						/><a
							class="video-link"
							data-lightgallery="item"
							href="https://youtu.be/6eeldaXgz-c"
							><img
								src="images/video-play-outline-90x90.png"
								alt=""
								width="90"
								height="90"
							/></a
						>
					</div>
				</div>
				<div class="col-lg-5">
					<div class="block-sm-min block-sm-min-custom">
						<h1
							class="font-weight-bold wow fadeInSmall"
							data-wow-delay=".1s"
						>
							Welcome to #1 Spa and Beauty Salon
						</h1>
						<p class="wow fadeInSmall" data-wow-delay=".2s">
							Classiquebrushes Salon offers the latest and highest
							quality services for you and all your family
							members.
						</p>
						<p class="wow fadeInSmall" data-wow-delay=".3s">
							We specialize in all beauty treatments and our team
							is fully professional and innovative, from makeup
							services to hair styling. Our clients appreciate our
							level of customer service and the skills of our
							stylists.
						</p>
						<a
							class="button button-default wow fadeInSmall"
							data-wow-delay=".4s"
							href="#"
							data-caption-animate="fadeInUp"
							data-caption-delay="450">Read more</a
						>
					</div>
				</div>
			</div>
		</div>
	</section>

	<!-- Products we use for-->
	<section class="section section-sm bg-default">
		<div class="container">
			<div class="row row-30 align-items-lg-center flex-lg-row-reverse">
				<div class="col-lg-7 wow fadeInSmall" data-wow-delay=".3s">
					<div class="img-custom-position">
						<img
							src="images/product-01-608x477.png"
							alt=""
							width="608"
							height="477"
						/>
					</div>
				</div>
				<div class="col-lg-5">
					<div class="product-about">
						<h1
							class="font-weight-bold wow fadeInSmall"
							data-wow-delay=".1s"
						>
							Products We Use for Our Treatments
						</h1>
						<div
							class="divider wow fadeInSmall"
							data-wow-delay=".2s"
						/>
						<p class="wow fadeInSmall" data-wow-delay=".3s">
							We use only the best products at Classiquebrushes. We
							pride ourselves on making sure our clients receive
							only the best service and products.
						</p>
						<ul class="list-inline">
							<li class="wow fadeInSmall" data-wow-delay=".1s">
								<a class="brand-link" href="#"
									><img
										src="images/brand-01-71x33.png"
										alt=""
										width="71"
										height="33"
									/></a
								>
							</li>
							<li class="wow fadeInSmall" data-wow-delay=".2s">
								<a class="brand-link" href="#"
									><img
										src="images/brand-02-64x57.png"
										alt=""
										width="64"
										height="57"
									/></a
								>
							</li>
							<li class="wow fadeInSmall" data-wow-delay=".3s">
								<a class="brand-link" href="#"
									><img
										src="images/brand-04-68x58.png"
										alt=""
										width="68"
										height="58"
									/></a
								>
							</li>
							<li class="wow fadeInSmall" data-wow-delay=".4s">
								<a class="brand-link" href="#"
									><img
										src="images/brand-03-76x47.png"
										alt=""
										width="76"
										height="47"
									/></a
								>
							</li>
						</ul>
					</div>
				</div>
			</div>
		</div>
	</section>
	<!-- Section Testimonials-->
	<section class="parallax-container" data-parallax-img="images/bg-01.jpeg">
		<div class="parallax-content section-lg">
			<div class="container text-center">
				<h1 class="wow fadeInSmall" data-wow-delay=".1s">
					Testimonials
				</h1>
				<div class="divider wow fadeInSmall" data-wow-delay=".2s" />
				<!-- Owl Carousel-->
				<div
					class="owl-carousel owl-carousel-blockquote"
					data-items="1"
					data-dots="true"
					data-nav="true"
					data-stage-padding="15"
					data-loop="true"
					data-margin="30"
					data-mouse-drag="false"
					data-autoplay="true"
				>
					<blockquote class="blockquote-sinple">
						<span class="blockquote-sinple-mark">
							<svg
								viewBox="0 0 63 51"
								fill="none"
								xmlns="https://www.w3.org/2000/svg"
							>
								<path
									d="M56.4453 3.61328C52.2786 5.37109 48.6979 8.13802 45.7031 11.9141C42.7083 15.625 41.2109 19.401 41.2109 23.2422C41.2109 24.8698 41.4062 26.2695 41.7969 27.4414C44.0755 25.6836 46.5495 24.8047 49.2188 24.8047C52.8646 24.8047 55.8919 25.9766 58.3008 28.3203C60.7747 30.599 62.0117 33.6914 62.0117 37.5977C62.0117 41.2435 60.7747 44.3034 58.3008 46.7773C55.8268 49.1862 52.7995 50.3906 49.2188 50.3906C44.0755 50.3906 40.1367 48.2747 37.4023 44.043C35.1237 40.5273 33.9844 36.1328 33.9844 30.8594C33.9844 24.1536 35.6771 18.1641 39.0625 12.8906C42.513 7.55208 47.6888 3.25521 54.5898 0L56.4453 3.61328ZM22.4609 3.61328C18.2943 5.37109 14.7135 8.13802 11.7188 11.9141C8.72396 15.625 7.22656 19.401 7.22656 23.2422C7.22656 24.8698 7.42188 26.2695 7.8125 27.4414C10.026 25.6836 12.5 24.8047 15.2344 24.8047C18.8151 24.8047 21.8424 25.9766 24.3164 28.3203C26.7904 30.599 28.0273 33.6914 28.0273 37.5977C28.0273 40.0065 27.4414 42.1875 26.2695 44.1406C25.0977 46.0938 23.5352 47.6237 21.582 48.7305C19.6289 49.8372 17.513 50.3906 15.2344 50.3906C10.0911 50.3906 6.15234 48.2747 3.41797 44.043C1.13932 40.5273 0 36.1328 0 30.8594C0 24.1536 1.69271 18.1641 5.07812 12.8906C8.52865 7.55208 13.7044 3.25521 20.6055 0L22.4609 3.61328Z"
								/>
							</svg></span
						>
						<p>
							<q class="heading-5"
								>I love my eyebrow design. I'm usually very
								picky about my eyebrows and not everyone can
								give me what I want. You are amazing. Thank you
								for the amazing job you’ve done, I’ll be
								recommending you to my friends!
							</q>
						</p>
						<cite class="cite">Sara Gonzalez</cite><span
							class="blockquote-sinple-position"
							>Regular Client</span
						>
					</blockquote>
					<blockquote class="blockquote-sinple">
						<span class="blockquote-sinple-mark">
							<svg
								viewBox="0 0 63 51"
								fill="none"
								xmlns="https://www.w3.org/2000/svg"
							>
								<path
									d="M56.4453 3.61328C52.2786 5.37109 48.6979 8.13802 45.7031 11.9141C42.7083 15.625 41.2109 19.401 41.2109 23.2422C41.2109 24.8698 41.4062 26.2695 41.7969 27.4414C44.0755 25.6836 46.5495 24.8047 49.2188 24.8047C52.8646 24.8047 55.8919 25.9766 58.3008 28.3203C60.7747 30.599 62.0117 33.6914 62.0117 37.5977C62.0117 41.2435 60.7747 44.3034 58.3008 46.7773C55.8268 49.1862 52.7995 50.3906 49.2188 50.3906C44.0755 50.3906 40.1367 48.2747 37.4023 44.043C35.1237 40.5273 33.9844 36.1328 33.9844 30.8594C33.9844 24.1536 35.6771 18.1641 39.0625 12.8906C42.513 7.55208 47.6888 3.25521 54.5898 0L56.4453 3.61328ZM22.4609 3.61328C18.2943 5.37109 14.7135 8.13802 11.7188 11.9141C8.72396 15.625 7.22656 19.401 7.22656 23.2422C7.22656 24.8698 7.42188 26.2695 7.8125 27.4414C10.026 25.6836 12.5 24.8047 15.2344 24.8047C18.8151 24.8047 21.8424 25.9766 24.3164 28.3203C26.7904 30.599 28.0273 33.6914 28.0273 37.5977C28.0273 40.0065 27.4414 42.1875 26.2695 44.1406C25.0977 46.0938 23.5352 47.6237 21.582 48.7305C19.6289 49.8372 17.513 50.3906 15.2344 50.3906C10.0911 50.3906 6.15234 48.2747 3.41797 44.043C1.13932 40.5273 0 36.1328 0 30.8594C0 24.1536 1.69271 18.1641 5.07812 12.8906C8.52865 7.55208 13.7044 3.25521 20.6055 0L22.4609 3.61328Z"
								/>
							</svg></span
						>
						<p>
							<q class="heading-5"
								>Linda cut my hair and did partial highlights
								and my experience was excellent! She took her
								time doing my hair and I am very pleased with
								the results. If you are still looking where to
								have your hair cut the best way, head for Relish
								Ruelle!
							</q>
						</p>
						<cite class="cite">Pamela Gray</cite><span
							class="blockquote-sinple-position"
							>Regular Client</span
						>
					</blockquote>
					<blockquote class="blockquote-sinple">
						<span class="blockquote-sinple-mark">
							<svg
								viewBox="0 0 63 51"
								fill="none"
								xmlns="https://www.w3.org/2000/svg"
							>
								<path
									d="M56.4453 3.61328C52.2786 5.37109 48.6979 8.13802 45.7031 11.9141C42.7083 15.625 41.2109 19.401 41.2109 23.2422C41.2109 24.8698 41.4062 26.2695 41.7969 27.4414C44.0755 25.6836 46.5495 24.8047 49.2188 24.8047C52.8646 24.8047 55.8919 25.9766 58.3008 28.3203C60.7747 30.599 62.0117 33.6914 62.0117 37.5977C62.0117 41.2435 60.7747 44.3034 58.3008 46.7773C55.8268 49.1862 52.7995 50.3906 49.2188 50.3906C44.0755 50.3906 40.1367 48.2747 37.4023 44.043C35.1237 40.5273 33.9844 36.1328 33.9844 30.8594C33.9844 24.1536 35.6771 18.1641 39.0625 12.8906C42.513 7.55208 47.6888 3.25521 54.5898 0L56.4453 3.61328ZM22.4609 3.61328C18.2943 5.37109 14.7135 8.13802 11.7188 11.9141C8.72396 15.625 7.22656 19.401 7.22656 23.2422C7.22656 24.8698 7.42188 26.2695 7.8125 27.4414C10.026 25.6836 12.5 24.8047 15.2344 24.8047C18.8151 24.8047 21.8424 25.9766 24.3164 28.3203C26.7904 30.599 28.0273 33.6914 28.0273 37.5977C28.0273 40.0065 27.4414 42.1875 26.2695 44.1406C25.0977 46.0938 23.5352 47.6237 21.582 48.7305C19.6289 49.8372 17.513 50.3906 15.2344 50.3906C10.0911 50.3906 6.15234 48.2747 3.41797 44.043C1.13932 40.5273 0 36.1328 0 30.8594C0 24.1536 1.69271 18.1641 5.07812 12.8906C8.52865 7.55208 13.7044 3.25521 20.6055 0L22.4609 3.61328Z"
								/>
							</svg></span
						>
						<p>
							<q class="heading-5"
								>Thank you for the best beauty service! I am
								very happy with the outcome. I feel fortunate to
								have met someone with years of training in
								makeup who is also bright and knowledgeable
								enough to determine my perfect style.
							</q>
						</p>
						<cite class="cite">Marilyn Ross</cite><span
							class="blockquote-sinple-position"
							>Regular Client</span
						>
					</blockquote>
				</div>
			</div>
		</div>
	</section>
	<!-- Section Gallery-->
	<section class="section section-lg section-bottom-0 bg-default text-center">
		<div class="container">
			<span
				class="icon icon-xl icon-primary-gradient mdi mdi-link-variant wow fadeInSmall"
				data-wow-delay=".1s"
			/>
			<h4 class="font-secondary-1 wow fadeInSmall" data-wow-delay=".2s">
				Follow our beautiful <a
					class="wow fadeInSmall"
					data-wow-delay=".3s"
					href="gallery-grid.html">gallery</a
				>
			</h4>
		</div>
		<div
			class="owl-carousel owl-carousel-instagram"
			data-lightgallery="group"
			data-items="1"
			data-xs-items="2"
			data-sm-items="3"
			data-md-items="3"
			data-lg-items="4"
			data-xl-items="5"
			data-autoplay="true"
			data-dots="true"
			data-nav="false"
			data-stage-padding="0"
			data-loop="true"
			data-margin="0"
			data-mouse-drag="true"
		>
			<div class="thumb-box">
				<div class="thumb-box-image">
					<a
						href="images/thumb-original-01-1200x784.jpeg"
						data-lightgallery="item"
						><img
							src="images/thumb-01-576x576.jpeg"
							alt=""
							width="576"
							height="576"
						/></a
					>
				</div>
			</div>
			<div class="thumb-box">
				<div class="thumb-box-image">
					<a
						href="images/thumb-original-02-1200x890.jpeg"
						data-lightgallery="item"
						><img
							src="images/thumb-02-576x576.jpeg"
							alt=""
							width="576"
							height="576"
						/></a
					>
				</div>
			</div>
			<div class="thumb-box">
				<div class="thumb-box-image">
					<a
						href="images/thumb-original-03-1200x782.jpeg"
						data-lightgallery="item"
						><img
							src="images/thumb-03-576x576.jpeg"
							alt=""
							width="576"
							height="576"
						/></a
					>
				</div>
			</div>
			<div class="thumb-box">
				<div class="thumb-box-image">
					<a
						href="images/thumb-04-576x576.jpeg"
						data-lightgallery="item"
						><img
							src="images/thumb-04-576x576.jpeg"
							alt=""
							width="576"
							height="576"
						/></a
					>
				</div>
			</div>
			<div class="thumb-box">
				<div class="thumb-box-image">
					<a
						href="images/thumb-05-576x576.jpeg"
						data-lightgallery="item"
						><img
							src="images/thumb-05-576x576.jpeg"
							alt=""
							width="576"
							height="576"
						/></a
					>
				</div>
			</div>
		</div>
	</section>
	<!-- Pre footer-->
<PreFooter/>
	<!-- Page Footer-->
	<Footer/>
</div>
