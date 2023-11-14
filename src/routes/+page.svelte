<script>
	import PeopleCard from '$lib/PeopleCard.svelte';
	import Section from '$lib/Section.svelte';
</script>

<svelte:head>
	<title>Marvin Raiser - Drones & Full-Stack Developer</title>
	<meta name="description" content="Marvin Raiser is a Full-Stack Developer and Drone Pilot, working at Fraunhofer IAO and studying at the Technical University of Munich." />
	<meta property="og:title" content="Marvin Raiser - Drones Full-Stack Developer" />
	<meta property="og:image" content="https://marvin.raiser.dev/MarvinRaiser.jpg" />
	<meta property="og:url" content="https://marvin.raiser.dev/" />
	<meta property="og:site_name" content="Marvin Raiser - Drones Full-Stack Developer" />
	<meta property="og:description" content="Marvin Raiser is a Full-Stack Developer and Drone Pilot, working at Fraunhofer IAO and studying at the Technical University of Munich." />
</svelte:head>

<Section title="Where I work">
	<PeopleCard
		src="fraunhofer.png"
		text="Since March 2020, I am a Full-Stack Developer and Drone Pilot at <a href='https://www.iao.fraunhofer.de/'>Fraunhofers Insitute of Industrial Engineering</a> creating WebApps connecting Industrial Smart Services with Drones and Robots."
	/>
	<PeopleCard
		src="Daimler_AG.svg"
		text="In the summer of 2015-2017, I did three Internships in Truck Pre-development for commercial vehicle applications from App Development with Qt to Embedded Systems Programming in C and Matlab Simulink."
	/>
</Section>

<!-- Add Project Diashow -->

<Section title="Where I study">
	<PeopleCard
		src="tum_csm.png"
		text="During my studies at the Technical University of Munich, I took my practical and seminar at the <a href='https://www.ce.cit.tum.de/en/air/home/'>Chair of Robotics and Embedded Systems</a>, working on a drone for powerline inspection."
	/>
	<PeopleCard
		src="tum.png"
		text="I am currently studying Computer Science in my bachelors at the <a href='https://www.tum.de/'>Technical University of Munich</a>, with a focus on Robotics, Artificial Intelligence and Drones trying to master Software Development."
	/>
	<PeopleCard
		src="weizmann.svg"
		text="As research intern at the <a href='https://www.weizmann.ac.il'>Weizmann Institute  of Science</a> within the <a href='https://www.weizmann.ch/int-summer-science-institute'>International Summer Science Institute Program</a>, I enjoyed a month of research, science and cultural exchange from all over the world."
	/>
	<PeopleCard
		src="wss-logo.svg"
		text="I graduated the <a href='https://wss-stuttgart.de'>Technical High School of the Werner Siemens School Stuttgart</a> in 2019 with a focus on Electrical Engineering and Computer Science. Extracurrics: Electric Mobility, Paramedic, Student Council."
	/>
</Section>

<!-- Add Social Media section -->

<Section title="Where I help and teach">
	<PeopleCard
		src="thw-muenchen-mitte.jpg"
		text="Since 2023, I am a recruit at the <a href='https://www.thw-muenchen-mitte.de/'>Federal Agency for Technical Relief</a> in Munich-Middle, where I help people in need e.g. in case of natural disasters or other emergencies."
	/>
	<PeopleCard
		src="dkfz-lifesciencelab.png"
		text="After being a scholar at the DKFZ's <a href='https://www.life-science-lab.org/cms/'>Heidelberger Life-Science Lab</a>, I remain as tutor for the next generation of young scientists, teaching them Computer Science, Ludology and Web Development."
	/>
	<PeopleCard
		src="Junior-Uni_Wuppertal_Logo.svg"
		text="At <a href='https://junioruni-wuppertal.de/'>Junior Uni Wuppertal</a>, I taught children aged 10-14 Scratch programming, guiding them from creating small games to programming a weather station with the use of the senseBox and BaKaRoS Project."
	/>
	<PeopleCard
		src="code+design.svg"
		text="Between 2018 and 2021 I was Campleader organizing several <a href='https://code.design'>Code+Design Camps</a> and Coach teaching children in App Development with Android Studio and Game Development using the Unity Engine."
	/>
</Section>

<Section title="Where I build & fly">
	<PeopleCard
		src="akamodell.svg"
		text="<a href='https://akamodell-muenchen.de'>The Akamodell München</a> is a student group of well-minded aircraft enthusiasts, where I work on my drones, assemble new aircraft with carbon fibre and help participating in international competitions."
	/>
	<PeopleCard
		src="AKKUS.svg"
		text="<a href='https://www.akkus-ev.de/'>Arbeitskreis Kopter</a> is a student group at the University Stuttgart about building and flying small racing, freestyle or cinematic drones with FPV, where I helped organzing a drone race."
	/>
</Section>

<Section title="Where I do WebDev voluntarily">
	<PeopleCard
		src="LabAlumni.svg"
		text="I joined the <a href='https://lab-alumni.de'>Alumni Network of Heidelbergs Life-Science Lab</a> after graduating, where I'm still in contact with other researchers. In the IT-Team we're working on a new website and provide infrastructure."
	/>
	<PeopleCard
		src="CampusCneipe.png"
		text="In 2022 I designed and programmed the website of TUM's <a href='https://c2.tum.de/'>Campus Cneipe</a> in Munich, where I try to be a regular guest and enjoying the best beer in town."
	/>
	<PeopleCard
		src="gamerrepublic.png"
		text="<a href='https://gamerrepublic.de'>Gamerrepublic</a> is a blog promoting the German video game culture and industry by providing a space for informative articles, in-depth reviews, and background information especially on indie games."
	/>
</Section>
