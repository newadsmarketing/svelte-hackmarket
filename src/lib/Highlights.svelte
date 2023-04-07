<script lang="ts">

	// Initializations & Exports:
	export let sdkLink: string;
	export let apiLink: string;

</script>

<!-- #################################################################################################### -->

<section>

	<!-- Open Source -->
	<div class="openSource">
		<img src="/images/integrations.svg" alt="Open Source">
		<div class="content right">
			<h3>배그핵</h3>
			<span>#아이템 ESP [ 아이콘 / 텍스터]

				#차량 표시
				
				#총기 표시
				
				#장비 표시
				
				#힐템 표시
				
				#탄약 표시
				
				#파츠 표시
				
				#에어드랍 표시
				
				#시체박스 표시
				
				#에임봇 [예측샷/탄낙차 계산 ]
				
				#에임봇 [ 부위별 조준가능 ]
				
				#에임봇키 [ 바꿀수 있음 ]
				
				#관전자 표시
				
				#파이터 모드
				
				#맵 레이더</span>
			<a href="https://noonoo40.tv" target="__blank">제품구매하기 ></a>
		</div>
	</div>

	<!-- Privacy -->
	<div class="privacy">
		<div class="content left">
			<h3>서든핵</h3>
			<span>
			
 스켈레톤 ( 스마트 월핵 )

 참스 월핵 (색상 조절 가능)

 박스 월핵

 거리표시

 체력바

 수류탄 추적

 오토에임
스무스 / 포브 / 부위 조절 가능

 바디샷
범위 / 확률 조절 가능

 무반동
반동조절 [ 0 % ~ 100 % 조절 ]

 방송 유도탄
범위 / 확률 조절 가능 / 몸 머리 근처 부위 선택

 에임고정
확률 [ 0 % ~ 100% 조절가능 ] / 적인식

 바디샷
범위 및 확률 [ 0 % ~ 100 % 조절 ]

 자동 고스트 스텝

 스피드핵 ( 조절 가능 )

 스카이 점프 ( 조절 가능 )

 바람샷

 오토 텔레포트

 선택 텔레포트

 자유시점

 자시 속도 조절

 노낙사

 총알재생

 수동 총속

 자동총속

 노장전

 고스트 채팅 무시

 즉시 리스폰

 카운트 무시

 유도 수류탄

 무기 인피니티

 캐릭터 인피니티

 장시간 노팅

 1초해제

 패킷킬
전체 / 선택 킬
메두사
무기변경 </span>
		</div>
		<img src="/images/safe.svg" alt="Privacy">
	</div>

	<!-- Devices -->
	<div class="devices">
		<img src="/images/compatibility.svg" alt="Devices">
		<div class="content right">
			<h3>옵치핵</h3>
			<span>
				[ ESP ]
			   
			   [+] 이름 ESP
			   
			   [+] 박스 ESP
			   
			   [+] 궁극기 ESP
			   
			   [+] 테두리 ESP
			   
			   [+] 히트박스 ESP
			   
			   [+] HUD 사이즈 조절 위치 조정 가능
			   
			   [+] 체력바 ESP (하단,상단 조정가능)
			   
			   [+] HUD ESP(상대 챔프 및 궁극기)
			   
			   [+] 시각적 ESP색 | 보이는 적 | 보이지 않는 적 | FOV범위에 들어온적
			   
			   
			   
				[ AIM BOT ]
			   
			   [+] 프리 스케일
			   
			   [+] 플릭샷 에임봇
			   
			   [+] 수직 고정 조절
			   
			   [+] 방패 확인 기능
			   
			   [+] 에임봇 키설정 가능
			   
			   [+] 유도탄(빡고정기능)
			   
			   [+] FOV 포브 조절 가능
			   
			   [+] 에임봇 다이나믹 FOV
			   
			   [+] 섬세한 에임봇 스무스 조절
			   
			   [+] 자동 거리계산 예측 에임봇 (한조,토르비욘,루시우 등등)
			   
			   </span>
		</div>
	</div>


</section>

<!-- #################################################################################################### -->

<style>

	section {
		flex-direction: column;
		padding: 4em 30vw;
		background-color: var(--tertiaryColor);
	}

	section > div {
		display: flex;
		align-items: center;
		margin: 2em 0;
	}

	div.content {
		display: flex;
		flex-direction: column;
		flex: 1;
		padding: 2em 0;
	}

	div.content.left {
		padding-right: 4em;
	}

	div.content.right {
		padding-left: 4em;
	}

	h3 {
		margin-bottom: .5em;
		font-size: 2em;
	}

	a {
		margin-top: 1em;
		color: var(--accentColor);
	}

	img {
		height: 15em;
	}

	@media screen and (max-width: 1270px) {
		section {
			padding: 4em 26vw;
		}
	}

	@media screen and (max-width: 1000px) {
		section {
			padding: 4em 22vw;
		}
	}

	@media screen and (max-width: 800px) {
		section {
			padding: 4em 18vw;
		}
	}

	@media screen and (max-width: 700px) {
		section {
			padding: 4em 14vw;
		}
	}

	@media screen and (max-width: 600px) {
		section {
			padding: 4em 10vw;
		}
	}

	@media screen and (max-width: 500px) {
		section {
			padding: 4em 6vw;
		}
		div.content.left {
			padding-right: 2em;
		}
		div.content.right {
			padding-left: 2em;
		}
	}

	@media screen and (max-width: 450px) {
		section {
			gap: 2em;
		}
		section > div {
			flex-direction: column;
			margin: 0;
		}
		div.content {
			padding: 1em 0 !important;
		}
		div.content.left {
			order: 1;
		}
	}
	
</style>