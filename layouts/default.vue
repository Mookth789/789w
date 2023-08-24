<template>
  <div>
   	
			<div class="container container22243">
				<div class="diygw-title diygw-top solid-bottom" style="color: white; background: #ff32ad">
					<div class="title flex1 text-center">หน้าหลัก</div>
				</div>
 

  <div>
  <slot/>
  </div>



		<div class="flex diygw-col-24 diygw-bottom">
					<div class="diygw-grid diygw-actions">
						<button class="diygw-action">
							<div class="diygw-grid-inner">
								<div class="diygw-grid-icon diygw-avatar" style="font-size: calc(35px - 12px); width: 35px; height: 35px">
									<NuxtLink to:='/'>
									<img mode="aspectFit" class="diygw-avatar-img" src="/static/grid1.png" />
									</NuxtLink>
								</div>
								<div class="diygw-grid-title">หน้าหลัก</div>
							</div>
						</button>

						<button class="diygw-action">
							<div class="diygw-grid-inner">
								<div class="diygw-grid-icon diygw-avatar" style="font-size: calc(35px - 12px); width: 35px; height: 35px">
									<NuxtLink to:='/mission'>
									<img mode="aspectFit" class="diygw-avatar-img" src="/static/grid2.png" />
									</NuxtLink>
								</div>
								<div class="diygw-grid-title">ภารกิจ</div>
							</div>
						</button>

						<button class="diygw-action">
							<div class="diygw-grid-inner">
								<div class="diygw-grid-icon diygw-avatar" style="font-size: calc(35px - 12px); width: 35px; height: 35px">
									<NuxtLink to:='/rank'>
									<img mode="aspectFit" class="diygw-avatar-img" src="/static/grid3.png" />
									</NuxtLink>
								</div>
								<div class="diygw-grid-title">อันดับ</div>
							</div>
						</button>


						<button class="diygw-action">
							<div class="diygw-grid-inner">
								<div class="diygw-grid-icon diygw-avatar" style="font-size: calc(35px - 12px); width: 35px; height: 35px">
									<NuxtLink to:='/chat'>
									<img mode="aspectFit" class="diygw-avatar-img" src="/static/grid4.png" />
									</NuxtLink>
								</div>
								<div class="diygw-grid-title">แชท</div>
							</div>
						</button>
						<button class="diygw-action">
							<div class="diygw-grid-inner">
								<div class="diygw-grid-icon diygw-avatar" style="font-size: calc(35px - 12px); width: 35px; height: 35px">
									<NuxtLink to:='/profile'>
									<img mode="aspectFit" class="diygw-avatar-img" src="/static/grid5.png" />
									</NuxtLink>
								</div>
								<div class="diygw-grid-title">ข้อมูล</div>
							</div>
						</button>
					</div>
				</div>
					
				
			




	<div class="version text-grey flex-direction-column flex diygw-col-24 justify-center align-center">
		<div>แพลตฟอร์มสร้างรายได้ออนไลน์</div>
					<div>www.example.com</div>
	</div>
				<div class="clearfix"></div>

</div>
</div>
</template>


<script>


</script>

<style>
@import "/assets/css/index.css";


</style>
