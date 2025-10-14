<script lang="ts">
	// Components
	import Summary from "$lib/components/layout/Summary.svelte";
	import Features from "$lib/components/layout/Features.svelte";
	import Testimonials from "$lib/components/layout/Testimonials.svelte";
	import CallToAction from "$lib/components/layout/CallToAction.svelte";
	import AboutTeaser from "$lib/components/layout/AboutTeaser.svelte";
	import LogoScroller from "$lib/components/layout/LogoScroller.svelte";
	import CenteredTextOnlyHero from "$lib/components/layout/hero-sections/CenteredTextOnlyHero.svelte";
</script>

<CenteredTextOnlyHero
	title="Train reliable AI agents in high-fidelity simulations of real work"
	subtitle="Fleet delivers the diverse, realistic work environments that frontier AI labs need to build agents that actually perform in production. From spec to simulation, we industrialize the creation of training environments for the next generation of AI."
	imageSrc="/generated/image-a-contemporary-interior-wall-with-a-subt.webp"
/>
<LogoScroller
	label="Trusted by frontier AI labs"
	logoUrls={[
		'https://cdn.brandfetch.io/openai.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/anthropic.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/deepmind.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/huggingface.co/w/400/h/400/logo'
	]}
/>

<Summary
	title="The challenge"
	text="AI agents fail in production because they're trained in synthetic environments that don't reflect real-world complexity. Frontier labs need diverse, high-fidelity simulations of actual work environments to build truly reliable agents. Fleet industrializes the creation of these training environments, transforming specifications into production-ready simulations that help AI labs build agents that actually perform when deployed."
/>

<Testimonials
	testimonials={[
		{
			name: "Wei Chen",
			position: "RL Researcher",
			company: "Top 2 AGI Lab",
			quote:
				"We meet with RL env companies every week at this point. I personally like your platform the best. Fleet cut our environment creation time from weeks to days, letting us test agent reliability across 10x more scenarios.",
			image: "/generated/image-professional-headshot-of-an-asian-male-r.webp"
		},
		{
			name: "Dr. Elena Vasquez",
			position: "ML Infrastructure Lead",
			company: "Frontier AI Research",
			quote:
				"Fleet's high-fidelity simulations finally gave us the diverse environments we needed. Our agents trained on Fleet outperform those trained on synthetic data by 40%, drastically reducing deployment risk.",
			image: "/generated/image-professional-headshot-of-a-woman-wearing.webp"
		},
		{
			name: "Marcus Johnson",
			position: "Agent Evaluation Lead",
			company: "Advanced AI Systems",
			quote:
				"The spec-driven approach saved us hundreds of engineering hours. We went from manually building test environments to automatically generating them at scale, accelerating our research timeline by months.",
			image: "/generated/image-professional-headshot-of-a-black-male-re.webp"
		}
	]}
/>

<Features
	title="Built for production reliability"
	subtitle="Fleet delivers the high-fidelity simulations and scalable infrastructure that frontier AI labs need to train agents that actually work in the real world."
	features={[
		{
			title: "High-fidelity work simulations",
			description:
				"Train agents in realistic replicas of actual job environments and workflows, not synthetic gaming scenarios. Our simulations capture the complexity of real white-collar work across law, finance, and tech domains.",
			imageSrc: "/generated/image-a-group-of-data-scientists-collaborating.webp"
		},
		{
			title: "Spec-driven environment generation",
			description:
				"Scale environment creation through our industrialized spec-to-code system. What takes competitors weeks to build manually, we generate in hours with automated QA and verification.",
			imageSrc: "/generated/image-a-creative-team-of-professionals-brainst.webp"
		},
		{
			title: "Production-ready agent training",
			description:
				"Bridge the gap between simulation and deployment with environments designed for reliability. Agents trained on Fleet outperform those trained on competitors' synthetic data in real-world tasks.",
			imageSrc: "/generated/image-ai-researchers-working-together-in-a-col.webp"
		},
		{
			title: "Diverse job environment library",
			description:
				"Access a growing library of work simulations spanning multiple industries and roles. Our platform provides the diverse training environments your agents need to generalize across domains.",
			imageSrc: "/generated/image-a-professional-digital-workspace-featuri.webp"
		},
		{
			title: "Real-time evaluation and observability",
			description:
				"Monitor agent behavior with comprehensive evaluation tools and observability features. Verify simulation fidelity and track agent performance with confidence throughout the training process.",
			imageSrc: "/generated/image-a-team-of-technical-professionals-gather.webp"
		},
		{
			title: "Enterprise SDK and API",
			description:
				"Integrate seamlessly with your existing RL workflows through our SDK designed for researchers and practitioners. Deploy on our hosted platform or integrate into your infrastructure via API.",
			imageSrc: "/generated/image-a-software-development-team-working-toge.webp"
		}
	]}
/>
<AboutTeaser />
<CallToAction
	title="Start training reliable agents today"
	subtitle="Join frontier AI labs already using Fleet"
	description="Stop wasting months building test environments manually. Get access to our spec-driven simulation platform and start training agents on high-fidelity work environments this week. Book a demo to see how Fleet can accelerate your agent research timeline."
	imageSrc="/generated/image-a-confident-ai-researcher-smiling-in-a-c.webp"
	callsToAction={[
		{
			href: "/contact",
			label: "Book a demo",
			variant: "primary"
		},
		{
			href: "/docs",
			label: "View documentation",
			variant: "secondary"
		}
	]}
/>
