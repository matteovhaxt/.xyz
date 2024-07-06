<script>
	import { CircleCheck, Github, Linkedin, Twitter } from 'lucide-svelte';
</script>

<svelte:head>
	<title>Home</title>
	<meta name="description" content="Matteo von Haxthausen's personal website" />
</svelte:head>

<section>
	<div class="hero min-h-screen">
		<div class="hero-content flex-col md:flex-row-reverse lg:w-2/3 gap-8">
			<img src="/images/portrait.png" alt="Matteo von Haxthausen" class="md:max-w-sm rounded-lg shadow-2xl" />
			<div class="flex flex-col items-start gap-8 py-8">
				<h3 class="text-xl font-bold">Hi, my name is</h3>
				<h1 class="text-5xl font-bold">Matteo von Haxthausen</h1>
				<p>
					As a digital innovator with experience ranging from startups to established tech
					companies, I specialize in building cutting-edge applications and platforms. My expertise
					spans from developing automated fintech solutions to crafting user-friendly interfaces,
					always with a focus on leveraging emerging technologies to create impactful digital
					products.
				</p>
				<div class="flex items-center gap-4">
					<button class="btn btn-primary">Get Started</button>
					<div class="flex gap-4">
						<a href="https://github.com/matteovhaxt">
							<Github />
						</a>
						<a href="https://twitter.com/matteovhaxt">
							<Twitter />
						</a>
						<a href="https://www.linkedin.com/in/matteovhaxt/">
							<Linkedin />
						</a>
					</div>
				</div>
			</div>
		</div>
	</div>
</section>

<section class="min-h-screen flex flex-col items-center gap-8 p-8">
	<h2 class="text-4xl font-bold">Skills</h2>
	<div class="grid grid-cols-1 md:grid-cols-2 gap-8">
		<div class="card bg-base-100 w-72 shadow-xl">
			<figure>
				<img src="/images/flutter-card.png" alt="Flutter" />
			</figure>
			<div class="card-body">
				<h2 class="card-title">
					Flutter
					<div class="badge badge-secondary">Dart</div>
				</h2>
				<p>Building mobile apps with Flutter.</p>
				<div class="card-actions justify-end">
					<div class="badge badge-outline">Bling</div>
					<div class="badge badge-outline">Earrn.</div>
				</div>
			</div>
		</div>
		<div class="card bg-base-100 w-72 shadow-xl">
			<figure>
				<img src="/images/svelte-card.png" alt="Svelte" />
			</figure>
			<div class="card-body">
				<h2 class="card-title">
					Svelte
					<div class="badge badge-secondary">Typescript</div>
				</h2>
				<p>Building web frontends with Svelte.</p>
				<div class="card-actions justify-end">
					<div class="badge badge-outline">LLM Studios</div>
					<div class="badge badge-outline">Website</div>
				</div>
			</div>
		</div>
		<div class="card bg-base-100 w-72 shadow-xl">
			<figure>
				<img src="/images/bun-elysia-card.png" alt="Bun + Elysia" />
			</figure>
			<div class="card-body">
				<h2 class="card-title">
					Bun + Elysia
					<div class="badge badge-secondary">Typescript</div>
				</h2>
				<p>Building web backends with Bun and Elysia.</p>
				<div class="card-actions justify-end">
					<div class="badge badge-outline">LLM Studios</div>
				</div>
			</div>
		</div>
		<div class="card bg-base-100 w-72 shadow-xl">
			<figure>
				<img src="/images/react-next-card.png" alt="React + Next.js" />
			</figure>
			<div class="card-body">
				<h2 class="card-title">
					React + Next
					<div class="badge badge-secondary">Typescript</div>
				</h2>
				<p>Building web frontends with React and Next.js.</p>
				<div class="card-actions justify-end">
					<div class="badge badge-outline">LLM Studios</div>
				</div>
			</div>
		</div>
	</div>
</section>

<section class="flex flex-col items-center justify-center gap-8 py-16 px-8">
	<h2 class="text-4xl font-bold">Work</h2>
	<ul class="timeline timeline-snap-icon max-md:timeline-compact timeline-vertical">
		<li>
			<div class="timeline-middle">
				<CircleCheck class="h-5 w-5" />
			</div>
			<div class="timeline-start lg:w-2/3 md:text-end">
				<time class="font-mono italic">Feb 2024 - Present</time>
				<div class="text-lg font-black">LLM Studios</div>
				At LLM Studios, we develop large language model applications from prototype to production. Our
				team advises customers on AI integration and investigates industry problems to identify innovative
				solutions. From initial concept to full implementation, we guide AI projects and help clients
				leverage this technology effectively.
			</div>
			<hr />
		</li>
		<li>
			<hr />
			<div class="timeline-middle">
				<CircleCheck class="h-5 w-5" />
			</div>
			<div class="timeline-end lg:w-2/3">
				<time class="font-mono italic">Mar 2023 - Feb 2024</time>
				<div class="text-lg font-black">Bling</div>
				While at Bling, I built the ETF trading frontend implementation, enhancing our investment offerings.
				I also refactored the money transfer feature, improving its efficiency and user experience. Additionally,
				I developed the cellular contract feature, expanding our service portfolio. These projects contributed
				to Bling's user-friendly financial platform, making investment and money management more accessible.
			</div>
			<hr />
		</li>
		<li>
			<div class="timeline-middle">
				<CircleCheck class="h-5 w-5" />
			</div>
			<div class="timeline-start lg:w-2/3 md:text-end">
				<time class="font-mono italic">Jul 2021 - Mar 2023</time>
				<div class="text-lg font-black">Earrn.</div>
				My first startup created an automated cashback rewards platform. I built a system that connected
				to users' bank accounts via PSD2, developed a Flutter mobile app, and used Firebase with TypeScript
				for the backend. Despite the innovative concept, the startup didn't succeed, but provided valuable
				entrepreneurial experience.
			</div>
			<hr />
		</li>
		<li>
			<hr />
			<div class="timeline-middle">
				<CircleCheck class="h-5 w-5" />
			</div>
			<div class="timeline-end lg:w-2/3">
				<time class="font-mono italic">Feb 2021 - Jul 2021</time>
				<div class="text-lg font-black">Academic Assistant</div>
				During my time at the university, I maintained the internal informational infrastructure for
				the Interaction Design department. I structured and curated content to ensure all students had
				a seamless experience accessing departmental resources and information.
			</div>
			<hr />
		</li>
	</ul>
</section>

<section class="flex flex-col items-center justify-center gap-8 py-16 px-8">
	<h2 class="text-4xl font-bold">Education</h2>
	<ul class="timeline timeline-snap-icon max-md:timeline-compact timeline-vertical">
		<li>
			<div class="timeline-middle">
				<CircleCheck class="h-5 w-5" />
			</div>
			<div class="timeline-start lg:w-2/3 md:text-end">
				<time class="font-mono italic">2020 - Present</time>
				<div class="text-lg font-black">CODE University</div>
				CODE University prepares students for the digital future. Its approach emphasizes interdisciplinary
				projects and self-directed learning, offering a forward-thinking educational model. As a student
				here, I've found the experience both challenging and rewarding.
			</div>
			<hr />
		</li>
		<li>
			<hr />
			<div class="timeline-middle">
				<CircleCheck class="h-5 w-5" />
			</div>
			<div class="timeline-end lg:w-2/3">
				<time class="font-mono italic">2019 - 2020</time>
				<div class="text-lg font-black">XU Exponential University of Applied Sciences</div>
				XU focuses on digital product development and emerging technologies, offering a modern approach
				to education. The curriculum emphasizes practical skills for the digital age, preparing students
				for future opportunities in technology and innovation.
			</div>
			<hr />
		</li>
	</ul>
</section>
