<script lang="ts">
	import Card from '$lib/components/Card.svelte';

	//Projects
	import ESPAdvanced from '$lib/projects/united esp.png';
	import GarageIndicator from '$lib/projects/rn_image_picker_lib_temp_41df1b5a-db0a-49d8-ad06-86d2f6a38f27.jpg';
	import Conway from '$lib/projects/conways.jpg';
	import VRPCB from '$lib/projects/Cases.jpg';
	import MEMX from '$lib/projects/memory-xplorer-blk-mrt378297.avif';
	import OE from '$lib/projects/thetahome.png';
	import WAVE from '$lib/projects/aaastar4.png';
	import STRAY from '$lib/projects/stray.png';
	import GREENIOT from '$lib/projects/greeniot.png';
	import MEDIA from '$lib/projects/media.png';
	import MULTICOl from '$lib/projects/aqua.jpg';
	import LOGIC from '$lib/projects/logic.png';
	import DRONE from '$lib/projects/DRONE.jpg';
	import IEEE from '$lib/projects/IEEE.png';

	import cypher from '$lib/projects/straycipheren1.ttf';

</script>

<svelte:head>
	<title>Projects</title>
	<meta name="description" content="A Wordle clone written in SvelteKit" />
</svelte:head>
<div class=" border-b-2 border-black/40">
<div class="card-grid">
	<Card 
		CardIMG={ESPAdvanced}
		CardTitle={"ESP Advanced"}
		CardDescription={"A Game Boy Advance-inspired passion project I built for emulation and as a personal dev tool. I learned a lot about SD card integration and graphics in the process."}
		CardHasLink={true}
		CardLink={"https://oshwlab.com/bowserko123/espgbahandheld"}
	/> 
	<Card 
		CardIMG={VRPCB}
		CardTitle={"SlimeVR Tracker PCB"}
		CardDescription={"Inspired by the SlimeVR Project, I saw an opportunity to shrink and cost-optimize VR position trackers. With my experience using the BME280 and passion for VR, I took it on as a fun side project. Along the way, I learned about OTA updates, movement vectors, and PCB design with 3D modeling."}
		CardHasLink={true}
		CardLink={"https://oshwlab.com/bowserko123/sdfss"}
		CardLinkText={"Project Design Files"}
	/>
	<Card 
		CardIMG={MEMX}
		CardTitle={"Memory Xplorer"}
		CardDescription={"A software-hardware project focused on memory interfacing as a dev tool for exploring memory communication and special features. It’s taught me valuable skills in software application design, hardware integration, and more."}
		CardHasLink={true}
		CardLink={"https://www.microchip.com/en-us/products/memory/memory-xplorer"}
		CardLinkText={"Project Page"}
	/>
	<Card 
		CardIMG={GREENIOT}
		CardTitle={"NAU Greenhouse IOT"}
		CardDescription={"For my senior capstone, we built wireless greenhouse condition trackers that uploaded data throughout the day for our sponsor. These sensors connected to an RPi MQTT server, which sent data to our capstone page. While live updates have stopped, sample data is still available."}
		CardHasLink={true}
		CardLink={"https://www.ceias.nau.edu/capstone/projects/EE/2021/NAUResearchGreenhouse-F20/"}
		CardLinkText={"Project Page"}
	/>
	<Card 
		CardIMG={MEDIA}
		CardTitle={"Home Media Server"}
		CardDescription={"I built a media server Docker stack to experiment with Docker and network connectivity. It operates across virtual networks, local networks, and subnets to automate media sourcing, downloading, and organizing for my Jellyfin server. Everything runs behind a VPN, allowing secure public access without exposing my network."}
		CardHasLink={false}
		CardLink={""}
		CardLinkText={""}
	/>
	<Card 
		CardIMG={OE}
		CardTitle={"Theta Tau Webpage"}
		CardDescription={"As a student, I served as Web Chair for Theta Tau’s Omicron Epsilon Chapter at NAU, where I built and launched the fraternity’s first and only website."}
		CardHasLink={true}
		CardLink={"https://thetataunau.online/"}
		CardLinkText={"Webpage Link"}
	/>
	<Card 
		CardIMG={MULTICOl}
		CardTitle={"Multi-Color PCB"}
		CardDescription={"This PCB project was a novelty experiment with JLCPCB’s new multicolor silkscreens, allowing custom images for under $5. As an anime fan, I created an oversized PCB featuring a \"useless\" anime girl to match its only function-powering an LED. It also served as a testbed for capacitor limitations on USB and LED power efficiency."}
		CardHasLink={false}
		CardLink={""}
		CardLinkText={""}
	/>
	<Card 
		CardIMG={LOGIC}
		CardTitle={"Saleae SWI Extension"}
		CardDescription={"I built this project to explore the Logic 2 Analyzer API and improve support for SWI EEPROMs. Existing one-wire analyzers couldn’t properly decode modern memories due to outdated timing constraints. Leveraging my knowledge of these memories, I developed a solution now available on Saleae’s page as an official community third-party analyzer. I also created a tech brief for Microchip on installation and usage."}
		CardHasLink={true}
		CardLink={"https://github.com/MicrochipTech/MicrochipSWILowLevelAnalyzer"}
		CardLinkText={"Github Repo"}
	/>
	<Card 
		CardIMG={DRONE}
		CardTitle={"FPV Drone"}
		CardDescription={"Inspired by the Flerkin FPV drone, I assembled my own using an external model kit, adding an FPV camera, reconfiguring a helicopter transmitter, and controlling the ESC and aileron servos. It was a fun project that taught me a lot about batteries and motor control. The drone reached speeds of ~40 mph and could fly for about 30 minutes before the video transmitter signal began to weaken."}
		CardHasLink={false}
		CardLink={""}
		CardLinkText={""}
	/>
	<Card 
		CardIMG={Conway}
		CardTitle={"Game Of Life Display"}
		CardDescription={"As a fan of Conway's Game of Life, I created a desk ornament by 3D printing a housing and using an ESP32-S3 to control a cheap P2 64x64 display. I loaded the game onto the display and enabled it to connect to my phone for custom images or animations. This project taught me about display operation, scan lines, and power management, especially since these displays can consume a lot of power when running at full capacity."}
		CardHasLink={false}
		CardLink={""}
		CardLinkText={""}
	/>
	<Card 
		CardIMG={WAVE}
		CardTitle={"Python Wave Collapse"}
		CardDescription={"I enjoy tackling coding challenges, and the Wave Collapse Algorithm intrigued me with its visual appeal. So, I created my own project to better understand the theory behind it. Using Python and the Pygame library, I displayed the map and applied my own version of the algorithm to generate cohesive, dynamic patterns, like the one shown in the project image."}
		CardHasLink={false}
		CardLink={""}
		CardLinkText={""}
	/>
	<Card 
		CardIMG={GarageIndicator}
		CardTitle={"Garage Door Indicator"}
		CardDescription={"This simple ESP8266 project was designed to help me avoid blocking my wife from the garage door to the house when I park. The module would toggle an LED when my car gets too close or is too far, preventing the garage from hitting my car. It also pings my PC to turn it on as soon as it detects with accuracy that I’ve arrived home."}
		CardHasLink={false}
		CardLink={""}
		CardLinkText={""}
	/>
	<Card 
		CardIMG={STRAY}
		CardTitle={"Stray Game Font"}
		CardDescription={"This project started as a fun gag, but it showcases my dedication. While playing the game \"Stray,\" I wanted to decode the world and understand the text. I ended up decoding the in-game alphabet, which became a cool visual effect. It also taught me how to integrate custom fonts into my projects."}
		CardHasLink={true}
		CardLink={cypher}
		CardLinkText={"Download Font"}
	/>
	<Card 
		CardIMG={IEEE}
		CardTitle={"IEEE Hackathon"}
		CardDescription={"In my freshman year at NAU, I got involved with the IEEE program and participated in my first hackathon, a line-following competition. My team won for being one of the few to finish the maze, using minimal motors and sensors, and a simple algorithm to complete the challenge."}
		CardHasLink={false}
		CardLink={""}
		CardLinkText={""}
	/>
	</div>
</div>

<style>
	.card-grid {
		display: flex;
		flex-wrap: wrap;
		justify-content: center;
		align-items: center;
	}
</style>
