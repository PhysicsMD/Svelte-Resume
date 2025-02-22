<script lang="ts">
	import Icon from '$lib/components/Icon.svelte';

	import HTML from '$lib/images/lang-icons/html-icon-1451x2048-69sehqrp.png';
	import RUST from '$lib/images/lang-icons/rust-icon-2048x2048-lfzjbuc7.png';
	import CSS from '$lib/images/lang-icons/5968242.png';
	import MATLIB from '$lib/images/lang-icons/7d509bd115a22d7910f5aaf1ddab6946.png';
	import C from '$lib/images/lang-icons/c-original-icon.png';
	import CPP from '$lib/images/lang-icons/c-plus-plus-logo.png';
	import CS from '$lib/images/lang-icons/c-sharp-c-icon-1822x2048-wuf3ijab.png';
	import VHDL from '$lib/images/lang-icons/file-type-light-systemverilog-icon-512x512-n6etzhly.png';
	import PY from '$lib/images/lang-icons/file-type-python.svg';
	import TS from '$lib/images/lang-icons/file-type-typescript-official.svg';
	import JAVA from '$lib/images/lang-icons/java-icon-1511x2048-6ikx8301.png';
	import JS from '$lib/images/lang-icons/javascript.svg';
	import NODE from '$lib/images/lang-icons/nodejs-plain.svg';
	import ASSM from '$lib/images/lang-icons/1658763190886.png';

	//technologies
	import CCS from '$lib/images/tech-icons/50741334-09224500-11e3-11e9-98a8-8186993eb772.png';
	import MONGO from '$lib/images/tech-icons/5c80e9-mongodb.svg';
	import LOGIC from '$lib/images/tech-icons/6400f6c7c6267887b402592a5035e7ce0242d30c.png';
	import SONAR from '$lib/images/tech-icons/949a653d-9573-4e6f-8a20-443126e55656@3x.png';
	import NETBEANS from '$lib/images/tech-icons/Apache_NetBeans_Logo.svg.png';
	import GIT from '$lib/images/tech-icons/Git_icon.svg.png';
	import JENKINS from '$lib/images/tech-icons/Jenkins_logo.svg.png';
	import MSPP from '$lib/images/tech-icons/Microsoft_Office_PowerPoint_(2019–present).svg.png';
	import MSW from '$lib/images/tech-icons/Microsoft_Office_Word_(2019–present).svg.png';
	import MRSTUDIO from '$lib/images/tech-icons/MounRiver.ico';
	import SVELTE from '$lib/images/tech-icons/Svelte_Logo.svg.png';
	import VSCODE from '$lib/images/tech-icons/Visual_Studio_Code_1.35_icon.svg.png';
	import ALTIUM from '$lib/images/tech-icons/altium-designer.png';
	import ARDUINO from '$lib/images/tech-icons/arduino-1.svg';
	import FUSION from '$lib/images/tech-icons/autodesk-fusion-360-product-icon.svg';
	import DOCKER from '$lib/images/tech-icons/docker.svg';
	import ECLIPSE from '$lib/images/tech-icons/eclipse-icon-512x479-6ivkqawb.png';
	import GITHUB from '$lib/images/tech-icons/github.png';
	import KIBANA from '$lib/images/tech-icons/kibana-icon-1537x2048-476gnmfc.png';
	import LIBERO from '$lib/images/tech-icons/libero.jpg';
	import ATSTUDIO from '$lib/images/tech-icons/mchp-studio-logo.avif';
	import MSX from '$lib/images/tech-icons/microsoft-excel-icon.png';
	import MCC from '$lib/images/tech-icons/mplab-code-configurator-transparent-background.avif';
	import MPDV from '$lib/images/tech-icons/mplab-datavisualizer-noback.avif';
	import HARMONY from '$lib/images/tech-icons/mplab-harmony-transparent-background.avif';
	import MPLABX from '$lib/images/tech-icons/mplab-xide-transparent-background.avif';
	import PLATIO from '$lib/images/tech-icons/platformio-icon-2048x2048-xl9ensxo.png';
	import VITE from '$lib/images/tech-icons/vitejs.svg';
	import EMBARCADERO from '$lib/images/tech-icons/delphi-logo-1024.png';
	import TAURI from '$lib/images/tech-icons/logo.DCjQDXhk.svg';
	import WIX from '$lib/images/tech-icons/wix-company-icon.png';
	import JIRA from '$lib/images/tech-icons/jira-icon-2048x2048-nmec2job.png';
	import CONF from '$lib/images/tech-icons/atlassian-confluence.png';
	import SOURCET from '$lib/images/tech-icons/sourcetree-icon-1626x2048-87bhm33f.png';
	import FIGMA from '$lib/images/tech-icons/fa4cd070-6a79-4e1b-b079-8b9b76408595-cover.png';
	import MQTT from '$lib/images/tech-icons/eclipse-mosquitto-logo.png';
	import AEM from '$lib/images/tech-icons/free-experience-manager-icon-download-in-svg-png-gif-file-formats--adobe-logo-suite-new-pack-files-folders-icons-2132673.webp';
	import SLACK from '$lib/images/tech-icons/2111615.png';
	import TEAMS from '$lib/images/tech-icons/ms-teams-meetings-integration.webp'

	import PFP from '$lib/images/self.jpg';
	import NAULOGO from '$lib/images/nauLogo.webp';
</script>

<svelte:head>
	<title>Home</title>
	<meta name="title" content="Resume">
	<meta name="description" content="A Website Resume" />
	<meta name="author" content="Alenn Wight">
</svelte:head>

<section>
	<h1>
		<span class="welcome">
			Welcome to my Web Resume
		</span>
	</h1>
	<img src={PFP} alt="pfp" class="w-72 pfp">
	<h4> I have a wide range of skills and hobbies, with web design being just one of them. 
		While my site’s style may be simple, functionality is what truly matters. 
		This platform serves as the best medium to showcase my unique and ever-growing 
		skill set. Whether you're interested in my experience or want to explore my projects, 
		you'll find everything organized for easy navigation.
	</h4>
	<br/>
	<img src={NAULOGO} alt="naulogo" class="w-50 logo">
	<h4>
		I earned my Bachelor’s in Electrical Engineering with a Computer Emphasis and a minor 
		in Computer Science from Northern Arizona University (NAU). My passion for 
		learning drives me to continually expand my expertise, which is reflected in 
		the diverse tools and technologies I work with. Some of my skills and hobbies, such as 
		participating in Capture The Flag (CTF) cybersecurity competitions, aren’t always easy 
		to list in a professional format, but they are a key part of my experience.
	</h4>
	<br/>
	<h4>
		I understand that some of my projects may lack detailed descriptions, so if you're 
		curious about anything, I encourage you to reach out. A picture may be worth a thousand 
		words, but it can't always capture the journey behind each project.
	</h4>
	<br/>
	<br/>
	<ol class="contact-info">
		<li><h3>Contact Information:</h3></li>
		<li>Phone: 623-776-6568 (Please text or email first, spam fills my voicemail quickly)</li>
		<li>Email: agw73@nau.edu</li>
		<li>Residing: Phoenix, Arizona, United States</li>
	</ol>

	<div class=" border-y-2 border-white/40">
		<h1>Languages</h1>
		<div class="icon-grid">
			<Icon IconImg={HTML} IconTitle={"HTML"}/>
			<Icon IconImg={CSS} IconTitle={"CSS"}/>
			<Icon IconImg={NODE} IconTitle={"Node JS"}/>
			<Icon IconImg={JS} IconTitle={"JavaScript"}/>
			<Icon IconImg={TS} IconTitle={"TypeScript"}/>
			<Icon IconImg={PY} IconTitle={"Python"}/>
			<Icon IconImg={C} IconTitle={"C"}/>
			<Icon IconImg={CPP} IconTitle={"C++"}/>
			<Icon IconImg={CS} IconTitle={"C#"}/>
			<Icon IconImg={MATLIB} IconTitle={"MATLAB"}/>
			<Icon IconImg={VHDL} IconTitle={"Verilog"}/>
			<Icon IconImg={JAVA} IconTitle={"Java"}/>
			<Icon IconImg={RUST} IconTitle={"Rust"}/>
			<Icon IconImg={ASSM} IconTitle={"Assembly"}/>
		</div>
	</div>
	<div class=" border-b-2 border-white/40">
	<h1>Technologies</h1>
	<div class="icon-grid">
		<Icon IconImg={VSCODE}  IconTitle={"CSS"}/>
		<Icon IconImg={MPLABX} IconTitle={"MPLAB X IDE"}/>
		<Icon IconImg={MCC} IconTitle={"Microchip Code Composer"}/>
		<Icon IconImg={MPDV} IconTitle={"MPLAB Data Visualizer"}/>
		<Icon IconImg={HARMONY} IconTitle={"MPLAB Harmony"}/> 
		<Icon IconImg={ATSTUDIO} IconTitle={"Atmel/Microchip Studio"}/>
		<Icon IconImg={GIT} IconTitle={"GIT"}/> 
		<Icon IconImg={GITHUB} IconTitle={"Github and Github Actions"}/> 
		<Icon IconImg={ARDUINO} IconTitle={"Arduin IDE"}/> 
		<Icon IconImg={MSW} IconTitle={"Microsoft Word"}/>
		<Icon IconImg={MSX} IconTitle={"Microsoft Excel"}/>
		<Icon IconImg={MSPP} IconTitle={"Microsoft Powerpoint"}/>
		<Icon IconImg={JIRA} IconTitle={"JIRA"}/> 
		<Icon IconImg={CONF} IconTitle={"Confluence"}/>
		<Icon IconImg={SOURCET} IconTitle={"SourceTree"}/>  
		<Icon IconImg={TEAMS} IconTitle={"Microsoft Teams"}/> 
		<Icon IconImg={SLACK} IconTitle={"Slack"}/>
		<Icon IconImg={LOGIC} IconTitle={"Saleae Logic 2"}/> 
		<Icon IconImg={AEM} IconTitle={"Adobe Experience Mangaer"}/>  
		<Icon IconImg={ALTIUM} IconTitle={"Altium Designer"}/> 
		<Icon IconImg={FUSION} IconTitle={"Fusion 360"}/>
		<Icon IconImg={SVELTE} IconTitle={"Svelte"}/>
		<Icon IconImg={VITE} IconTitle={"Vite"}/>
		<Icon IconImg={TAURI} IconTitle={"Tauri"}/>
		<Icon IconImg={WIX} IconTitle={"Wix Toolset"}/>
		<Icon IconImg={MQTT} IconTitle={"MQTT"}/> 
		<Icon IconImg={MONGO} IconTitle={"Mongo DB"}/> 
		<Icon IconImg={ECLIPSE} IconTitle={"Eclipse IDE"}/> 
		<Icon IconImg={KIBANA} IconTitle={"Kibana"}/> 
		<Icon IconImg={LIBERO} IconTitle={"Libero"}/>
		<Icon IconImg={PLATIO} IconTitle={"Platform IO"}/>
		<Icon IconImg={EMBARCADERO} IconTitle={"Embarcadero"}/> 
		<Icon IconImg={NETBEANS} IconTitle={"Netbeans IDE"}/>
		<Icon IconImg={MRSTUDIO} IconTitle={"Moun River Studio"}/> 
		<Icon IconImg={CCS} IconTitle={"Code Composer Studio"}/> 
		<Icon IconImg={SONAR} IconTitle={"SonarQube"}/> 
		<Icon IconImg={JENKINS} IconTitle={"Jenkins"}/> 
		<Icon IconImg={DOCKER} IconTitle={"Docker"}/>
		<Icon IconImg={FIGMA} IconTitle={"Figma"}/>  
	</div>
	</div>
</section>

<style>
	section {
		display: block;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		flex: 0.6;
		color: white;
	}

	h1 {
		width: 100%;
	}

	.welcome {
		display: block;
		width: 100%;
		height: 0;
		padding: 0 0 100px 0;
	}

	.icon-grid {
		display: flex;
		flex-wrap: wrap;
		justify-content: center;
		align-items: center;
	}

	.pfp{
		float: left;
		margin: 10px;
		border: 2px double;
	}
	.logo{
		float: right;
		width: 10em;
		margin: 10px;
	}

	h4{
		padding-top: 10px;
	}

	.contact-info {
    list-style-type: none;
    padding: 0;
	justify-items: center;
    max-width: 600px;
    margin: 0 auto;
	}

	.contact-info li {
    	margin-bottom: 10px;
	}

	.contact-info h3 {
    	font-size: 1.3rem;
    	margin-bottom: 15px;
    	font-weight: 600;
	}

</style>
