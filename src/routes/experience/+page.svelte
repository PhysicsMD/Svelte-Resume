<script lang="ts">
	import ExperienceCard from '$lib/components/ExperienceCard.svelte';

	import MCHPLOGO from '$lib/exp-img/Microchip_Technology_logo.svg.png';
	import InterfaceLOGO from '$lib/exp-img/1680035393_interfacelogo.png';
	import TXRHLOGO from '$lib/exp-img/Texas_Roadhouse-Logo.wine.png';
	import NAULOGO from '$lib/exp-img/NAU_Ligature_Identity_281-3514_RGB-1-301x116.png';
	import BGIBLOGO from '$lib/exp-img/BGIBlocktransparent.png';
	import GeronimoLOGO from '$lib/exp-img/48390_1438123391_2296.jpg';
</script>

<svelte:head>
	<title>Experience</title>
	<meta name="description" content="About me" />
</svelte:head>

<div class="text-column">
	<ExperienceCard
		ShardCompany={"Microchip Inc."}
		ShardRole={"Application Engineer - MPD"}
		ShardDates={"Dec 2022 - Present"}
    	ShardDescription={"As an Applications Engineer in Microchip’s Memory Products Division, I contribute to the development, validation, and support of Microchip’s memory solutions. My role encompasses a broad range of responsibilities, including authoring and maintaining technical documentation such as datasheets, Design and Operational Specifications (DOSs), application notes, technical briefs, and errata. Additionally, I provide direct technical support to customers, advising on product integration and troubleshooting issues. \nI am actively involved in the creation and maintenance of developmental and promotional projects, as well as the validation of hardware used to qualify silicon for production release. Through this work, I have gained extensive experience with Microchip’s EEPROM, Flash, EERAM, RTCC EEPROM, and SRAM products. \nMy experience extends across a wide range of Microchip’s microcontrollers and processors, including PIC8, PIC24, and PIC32, as well as Atmel MCUs, PolarFire FPGAs, SmartFusion2, and SAM MPUs. I have worked with communication protocols such as I²C, SPI, UNIO, Microwire (MW), 3-Wire, SDI, and SQI. \n Additionally, I have contributed to the development and enhancement of MPLAB Code Configurator (MCC) modules, improving their functionality within MPLAB X IDE to streamline code generation for customers. My work at Microchip has provided me with a deep understanding of memory technologies, embedded systems, and hardware validation processes."}
    	ShardLocation={"Chandler, AZ"}
		ShardIMG={MCHPLOGO}
	/>
	<ExperienceCard
		ShardCompany={"Interface Inc."}
		ShardRole={"ASM Assembler - DLC"}
		ShardDates={"Aug 2022 - Dec 2022"}
    	ShardDescription={"As a Load Cell Technician, I worked with high-precision downhole load cells, focusing on calibration, testing, and characterization of tension circuits. My responsibilities included trimming and balancing Delta bridges, voltage dividers, and thermal resistance circuits to ensure accurate measurements across varying external conditions. \nI gained hands-on experience with digital multimeters, environmental test chambers, electrostatic discharge (ESD) testing, and high-stress hydraulic testing to validate load cell performance and reliability."}
    	ShardLocation={"Scottsdale, AZ"}
		ShardIMG={InterfaceLOGO}
	/>
	<ExperienceCard
		ShardCompany={"Texas Roadhouse"}
		ShardRole={"Server Assistant"}
		ShardDates={"May 2018 - Nov 2021"}
    	ShardDescription={"During my time as a Server Assistant and Busser at the Flagstaff and Happy Valley Texas Roadhouse locations, I was recognized with two Employee of the Month awards (Happy Valley - Jul 2018, Flagstaff - Nov 2018) for my dedication and strong work ethic. My role involved maintaining a clean and organized restaurant, assisting with table turnover, and supporting hosts and servers in various tasks to ensure a seamless dining experience. Additionally, I contributed to cold prep work, supporting the kitchen team with essential tasks."}
    	ShardLocation={"Glendale/Flagstaff, AZ"}
		ShardIMG={TXRHLOGO}
	/>
	<ExperienceCard
		ShardCompany={"Northern Arizona University"}
		ShardRole={"EE188 Teaching Assistant"}
		ShardDates={"Jan  2019 - May 2020"}
    	ShardDescription={"As a Teaching Assistant for EE188, an introductory course in electrical engineering, I supported students in mastering key concepts including DC and AC circuit analysis, operational amplifiers, transducers, transformers, and AC power. My responsibilities included hosting study and tutoring sessions, grading homework and exams (even beyond my expected role), and creating fair and challenging exam and homework questions to assess student understanding effectively."}
    	ShardLocation={"Flagstaff, AZ"}
		ShardIMG={NAULOGO}
	/>
	<ExperienceCard
		ShardCompany={"IB Tutors"}
		ShardRole={"Math Tutor"}
		ShardDates={"Aug 2016 - May 2017"}
    	ShardDescription={"As part of a senior project led by Shannon Liu, I participated in hosting study sessions across multiple subjects to raise average grades throughout the school. My primary focus was serving as the main math tutor, assisting students with topics ranging from Algebra to Calculus 1. Through this initiative, we achieved a marginal increase in student performance while enhancing our own communication skills and solidifying our understanding of the material."}
    	ShardLocation={"Glendale, AZ"}
		ShardIMG={BGIBLOGO}
	/>
	<ExperienceCard
		ShardCompany={"BSA Camp Geronimo"}
		ShardRole={"Merit Badge Councelor"}
		ShardDates={"Summers of '13, '14 and '15"}
    	ShardDescription={"During multiple summers at BSA Camp Geronimo, I served as a Merit Badge Counselor, teaching a wide range of subjects to scouts. I taught 3-4 classes per week, each with an average of 40 students, for 2 and a half months each summer. My lessons covered a variety of merit badges, including Weather, Rifle Shooting, Nature, Bird Study, Forestry, Insect Study, Sustainability, and Environmental Science. While spending the full summer at camp, I resided in cabins and was fully immersed in the camp environment, delivering engaging and educational experiences for the scouts."}
    	ShardLocation={"Payson, AZ"}
		ShardIMG={GeronimoLOGO}
	/>
</div>
