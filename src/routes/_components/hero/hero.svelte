<script lang="ts">
	import { Button } from '$lib/ui/button';
	import { ArrowRight, MoveRight } from 'lucide-svelte';
</script>



<section id="hero" class="w-full p-2 sm:p-4">
	<div
		class="w-full overflow-hidden rounded-md bg-green-50 items-center flex flex-col"
	>
		<div class="text-center w-full max-w-4xl py-16 pb-8 px-2 sm:px-6 sm:py-16 lg:py-20">
			<div class="text-primary capitlize text-sm mb-2">
				IN-PRODUCT MICROSURVEYS FOR WEB-APPLICATIONS
			</div>
			<h1 class="text-4xl font-bold font-serif text-green-950 md:text-5xl lg:text-6xl">
				We are creators & enthusiasts of <span class="italic">side-startups!</span>
			</h1>
			<p class="mt-6 text-lg leading-8 text-gray-600">
				Sideups is a community of creators and enthusiasts who are passionate
			about launching and growing their side-startups.
			</p>

			<div class="mt-10 flex items-center justify-center gap-2 flex-col sm:flex-row">
				<Button 
                    href="/account/sign-up"
                class="text-base h-12 shadow-md w-full sm:w-auto"
					>Showcase your startup
					<MoveRight class="ml-2 h-5 w-5 opacity-80" />
				</Button>
				<Button
                    href="/demo"
                class="text-base h-12 w-full sm:w-auto" size="lg" variant="outline"
					>See projects</Button
				>
			</div>
		</div>
	</div>
</section>

