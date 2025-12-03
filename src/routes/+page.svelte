<script lang="ts">
	// Components
	import Summary from "$lib/components/layout/Summary.svelte";
	import Features from "$lib/components/layout/Features.svelte";
	import Testimonials from "$lib/components/layout/Testimonials.svelte";
	import CallToAction from "$lib/components/layout/CallToAction.svelte";
	import AboutTeaser from "$lib/components/layout/AboutTeaser.svelte";
	import LogoScroller from "$lib/components/layout/LogoScroller.svelte";
	import CustomerCardHero from "$lib/components/layout/hero-sections/CustomerCardHero.svelte";

	// Icons
	import IconShieldCheck from "~icons/lucide/shield-check";
	import IconZap from "~icons/lucide/zap";
	import IconActivity from "~icons/lucide/activity";
	import IconNetwork from "~icons/lucide/network";
	import IconLock from "~icons/lucide/lock";
	import IconPlug from "~icons/lucide/plug";
</script>

<CustomerCardHero
	centered={true}
	title="The world's first tech-enabled bullion liquidity network"
	subtitle="Real-time vault-verified trading that connects refiners, dealers, and institutional buyers in a trusted marketplace."
	customers={[
		{
			name: "Michael Torres",
			position: "Senior Bullion Dealer",
			imageSrc: "/generated/image-centered-portrait-of-a-professional-male.webp"
		},
		{
			name: "Sarah Chen",
			position: "Silver Refinery Operations",
			imageSrc: "/generated/image-centered-portrait-of-a-professional-fema.webp"
		},
		{
			name: "David Richardson",
			position: "Metals Trading Director",
			imageSrc: "/generated/image-centered-portrait-of-a-professional-male.webp"
		},
		{
			name: "Jennifer Morrison",
			position: "Vault Storage Manager",
			imageSrc: "/generated/image-centered-portrait-of-a-professional-fema.webp"
		},
		{
			name: "Robert Martinez",
			position: "Precious Metals Buyer",
			imageSrc: "/generated/image-centered-portrait-of-a-professional-male.webp"
		}
	]}
/>
<LogoScroller
	label="Trusted by industry leaders"
	logoUrls={[
		'https://cdn.brandfetch.io/brinks.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/loomis.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/asahi.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/hsbc.com/w/400/h/400/logo'
	]}
/>

<Summary
	title="Transforming precious metals trading"
	text="Athanor connects refiners, dealers, and institutional buyers through real-time vault-verified trading in the $1.4 trillion bullion market. We eliminate the opacity and settlement delays that have plagued traditional supply chains, replacing them with instant liquidity and complete transparency. Every transaction is backed by physical assets verified in segregated vaults, giving participants the confidence to trade at scale."
/>

<Testimonials
	testimonials={[
		{
			name: "Marcus Thornton",
			position: "Senior Bullion Dealer",
			company: "Apex Metals Trading",
			quote:
				"Athanor transformed our silver sourcing from a three-day settlement process to real-time execution. The vault-verified transparency gives us complete confidence in every transaction, and we've cut our liquidity costs by 40%.",
			image: "/generated/image-medium-shot-of-a-professional-male-bulli.webp"
		},
		{
			name: "Diana Patel",
			position: "Refinery Operations Director",
			company: "Silverstream Refining",
			quote:
				"Before Athanor, opaque pricing meant we left money on the table with every sale. Now we see real-time market depth and execute instantly. The platform eliminated counterparty risk through vault verification, giving us the confidence to scale.",
			image: "/generated/image-medium-shot-of-a-professional-female-ref.webp"
		},
		{
			name: "Henrik Bergström",
			position: "Vault Storage Director",
			company: "Nordic Secure Vaults",
			quote:
				"Connecting our segregated storage infrastructure to Athanor's network unlocked immediate value. Our clients now access instant liquidity on their holdings, and we've increased transaction volume by 60% while maintaining our strict security standards.",
			image: "/generated/image-medium-shot-of-a-professional-male-vault.webp"
		}
	]}
/>

<Features
	title="Built for precision and trust"
	subtitle="The infrastructure that transforms how precious metals are traded"
	features={[
		{
			title: "Vault-verified transparency",
			description:
				"Every ounce of bullion on our platform is verified in real-time by segregated vault providers, eliminating opacity and establishing trust in every transaction.",
			icon: IconShieldCheck
		},
		{
			title: "Instant settlement",
			description:
				"Complete trades in minutes instead of weeks with our tech-enabled settlement infrastructure that delivers the liquidity refiners demand.",
			icon: IconZap
		},
		{
			title: "Real-time market pricing",
			description:
				"Access live pricing data and transparent price discovery across our entire network, replacing opaque traditional pricing with market clarity.",
			icon: IconActivity
		},
		{
			title: "Three-tier liquidity network",
			description:
				"Connect directly with vault providers, bullion dealers, and silver refiners in a unified marketplace that scales with transaction volume.",
			icon: IconNetwork
		},
		{
			title: "Institutional-grade security",
			description:
				"Enterprise security architecture built for the $1.4T bullion market, ensuring your assets and data remain protected at every level.",
			icon: IconLock
		},
		{
			title: "Seamless integration",
			description:
				"API-first platform that integrates with your existing trading workflows, minimizing disruption while maximizing operational efficiency.",
			icon: IconPlug
		}
	]}
/>
<AboutTeaser />
<CallToAction
	title="Join the liquidity revolution"
	subtitle="Start trading vault-verified bullion today"
	description="Every day without Athanor is a day of opaque pricing, slow settlement, and missed opportunities. Leading refiners and dealers are already trading with instant liquidity and complete transparency. Join the network transforming the $1.4T bullion market."
	imageSrc="/generated/image-a-professional-bullion-dealer-stands-con.webp"
	callsToAction={[
		{
			href: "/contact",
			label: "Request platform access",
			variant: "primary"
		},
		{
			href: "/about",
			label: "Learn how it works",
			variant: "secondary"
		}
	]}
/>
