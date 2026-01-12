<script lang="ts">
    // Golf apparel and lifestyle images
    const heroImage = "https://images.unsplash.com/photo-1535131749006-b7f58c99034b?q=80&w=2560&auto=format&fit=crop";
    const fabricDetail = "https://images.unsplash.com/photo-1489987707025-afc232f7ea0f?q=80&w=1000&auto=format&fit=crop";
    const golfCourse = "https://images.unsplash.com/photo-1587174486073-ae5e5cff23aa?q=80&w=1000&auto=format&fit=crop";
    const lifestyleCity = "https://images.unsplash.com/photo-1507003211169-0a1dd7228f2d?q=80&w=2560&auto=format&fit=crop";
    const golfAction = "https://images.unsplash.com/photo-1592919505780-303950717480?q=80&w=1000&auto=format&fit=crop";
    const productDetail = "https://images.unsplash.com/photo-1620799140408-edc6dcb6d633?q=80&w=1000&auto=format&fit=crop";
    const golfWalk = "https://images.unsplash.com/photo-1587174486073-ae5e5cff23aa?q=80&w=1000&auto=format&fit=crop";
    const collarDetail = "https://images.unsplash.com/photo-1594938298603-c8148c4dae35?q=80&w=1000&auto=format&fit=crop";
    const courseWide = "https://images.unsplash.com/photo-1535131749006-b7f58c99034b?q=80&w=2560&auto=format&fit=crop";
    const clubhouse = "https://images.unsplash.com/photo-1566577134770-3d85bb3a9cc4?q=80&w=1000&auto=format&fit=crop";
    const accessories = "https://images.unsplash.com/photo-1461896836934-ffe607ba8211?q=80&w=1000&auto=format&fit=crop";
    const lifestyleOutfit = "https://images.unsplash.com/photo-1490578474895-699cd4e2cf59?q=80&w=2560&auto=format&fit=crop";
    const ctaShop = "https://images.unsplash.com/photo-1535131749006-b7f58c99034b?q=80&w=2000&auto=format&fit=crop";
    const ctaStory = "https://images.unsplash.com/photo-1587174486073-ae5e5cff23aa?q=80&w=2000&auto=format&fit=crop";
</script>

<div class="w-full">
    <!-- Hero Section -->
    <section class="w-full mb-16 md:mb-24 px-4 md:px-6 max-w-[1600px] mx-auto">
        <div class="relative w-full aspect-[16/9] md:aspect-[21/9] overflow-hidden">
            <img src={heroImage} alt="Quiet luxury golf style" class="w-full h-full object-cover" />
            <div class="absolute inset-0 bg-black/20"></div>
            <div class="absolute inset-0 flex flex-col items-center justify-center text-white text-center p-6">
                <h1 class="font-display text-5xl md:text-7xl mb-6">Quiet Luxury.<br/>Refined Golf.</h1>
                <p class="text-lg font-light mb-8 max-w-2xl">Premium fabrics, minimalist design, and course-to-city silhouettes for the modern golfer.</p>
                <button class="bg-white text-black px-8 py-3 text-xs uppercase tracking-widest hover:bg-gray-100 transition-colors">
                    Shop Collection
                </button>
            </div>
        </div>
    </section>

    <!-- Brand Philosophy -->
    <section class="max-w-[1200px] mx-auto px-6 mb-24 md:mb-32">
        <div class="grid grid-cols-1 md:grid-cols-2 gap-12 md:gap-24">
            <div>
                <h2 class="font-display text-3xl md:text-4xl text-gray-900 mb-8">Modern Golf, Timeless Style</h2>
                <div class="text-gray-600 text-sm leading-relaxed space-y-4 max-w-md font-light">
                    <p>
                        We deliver quiet, modern golf style through premium fabrics, minimalist design, and versatile silhouettes that transition seamlessly from course to city.
                    </p>
                    <p>
                        For the modern golfer who values refined on-course apparel without loud logos and dated, performance-first golfwear. This is golf style reimagined.
                    </p>
                </div>
            </div>
            <div class="grid grid-cols-2 gap-y-6 text-[11px] uppercase tracking-wider">
                <div class="text-gray-400">Founded</div>
                <div class="text-gray-900">2024</div>

                <div class="text-gray-400">Founders</div>
                <div class="text-gray-900">Malte Berresheim<br/>Philip Rottschäfer</div>

                <div class="text-gray-400">Philosophy</div>
                <div class="text-gray-900">Quiet Luxury Meets<br/>Modern Golf</div>

                <div class="col-span-2 pt-6 border-t border-gray-100 mt-2">
                    <div class="text-gray-400 mb-1">Approach</div>
                    <div class="text-gray-900">Strict brand discipline. Timeless design. Premium essentials.</div>
                </div>
            </div>
        </div>
    </section>

    <!-- Product Showcase Grid 1 -->
    <section class="max-w-[1600px] mx-auto px-6 mb-24 md:mb-32">
        <div class="grid grid-cols-1 md:grid-cols-12 gap-6 items-start">
            <div class="md:col-span-5 md:col-start-2">
                <img src={fabricDetail} alt="Premium fabric detail" class="w-full aspect-[3/4] object-cover mb-4" />
                <p class="text-xs text-gray-400 font-light max-w-xs mt-8 leading-relaxed">
                    Every piece begins with premium fabrics sourced for their exceptional quality, durability, and refined hand feel. Materials that perform on the course and elevate your everyday.
                </p>
            </div>
            <div class="md:col-span-5 md:col-start-8 md:mt-32">
                 <img src={golfCourse} alt="On-course style" class="w-full aspect-square object-cover" />
            </div>
        </div>
    </section>

    <!-- Full Width Lifestyle -->
    <section class="max-w-[1600px] mx-auto px-6 mb-24 md:mb-32">
        <img src={lifestyleCity} alt="Course to city style" class="w-full aspect-[16/9] md:aspect-[21/9] object-cover" />
    </section>

    <!-- Features Grid -->
    <section class="max-w-[1600px] mx-auto px-6 mb-24 md:mb-32">
        <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
            <div>
                <img src={golfAction} alt="Performance on course" class="w-full aspect-[3/4] object-cover" />
            </div>
            <div class="flex flex-col justify-between">
                <img src={productDetail} alt="Design detail" class="w-full aspect-[3/4] object-cover mb-8" />
                <div class="max-w-xs ml-auto">
                     <p class="text-xs text-gray-400 font-light leading-relaxed">
                        Minimalist design meets functional excellence. Clean lines, refined details, and a commitment to quality that transcends trends. Golf apparel designed for those who appreciate understated elegance.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- Product Detail Grid -->
    <section class="max-w-[1600px] mx-auto px-6 mb-24 md:mb-32">
        <div class="grid grid-cols-1 md:grid-cols-12 gap-6 items-end">
             <div class="md:col-span-5">
                <img src={collarDetail} alt="Collar detail" class="w-full aspect-[4/5] object-cover" />
            </div>
            <div class="md:col-span-7">
                <img src={golfWalk} alt="Walking the course" class="w-full aspect-[4/3] object-cover" />
            </div>
        </div>
    </section>

    <!-- Large Course Image -->
    <section class="w-full mb-24 md:mb-32">
        <img src={courseWide} alt="Golf course lifestyle" class="w-full h-[80vh] object-cover" />
    </section>

    <!-- Lifestyle Grid & Text -->
    <section class="max-w-[1600px] mx-auto px-6 mb-24 md:mb-32">
        <div class="grid grid-cols-1 md:grid-cols-2 gap-6 mb-16 items-start">
            <img src={clubhouse} alt="Clubhouse style" class="w-full aspect-[3/4] object-cover" />
            <div class="md:pt-32">
                 <img src={accessories} alt="Golf accessories" class="w-full aspect-[3/4] object-cover" />
            </div>
        </div>
        <div class="flex justify-end">
             <p class="text-xs text-gray-400 font-light max-w-md leading-relaxed">
                From the first tee to evening drinks at the clubhouse, our pieces transition effortlessly. Premium golf essentials designed with strict brand discipline, capturing the quiet-luxury golfer and scaling to a global lifestyle brand.
            </p>
        </div>
    </section>

    <!-- Wide Lifestyle Image -->
    <section class="w-full mb-24 md:mb-32">
        <img src={lifestyleOutfit} alt="Lifestyle versatility" class="w-full h-[70vh] object-cover" />
    </section>

    <!-- Brand Values -->
    <section class="max-w-[1600px] mx-auto px-6 mb-24 md:mb-32">
        <div class="max-w-md">
            <p class="text-xs text-gray-400 font-light leading-relaxed">
                We reach modern golfers through DTC e-commerce and club partnerships, overcoming hype fatigue with disciplined, timeless design. Every piece reflects our commitment to quality, refinement, and the quiet confidence of understated luxury.
            </p>
        </div>
    </section>

    <!-- Collections Preview -->
    <section class="max-w-[1600px] mx-auto px-6 mb-32 md:mb-40">
        <h2 class="font-display text-3xl mb-12">Essential Collections</h2>
        <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
            <div class="group cursor-pointer">
                <div class="aspect-[3/4] bg-gray-100 mb-4 overflow-hidden">
                    <img src={fabricDetail} alt="Polos" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500" />
                </div>
                <h3 class="text-sm uppercase tracking-wider mb-1">Polos</h3>
                <p class="text-xs text-gray-400">From $120</p>
            </div>
            <div class="group cursor-pointer">
                <div class="aspect-[3/4] bg-gray-100 mb-4 overflow-hidden">
                    <img src={productDetail} alt="Pants" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500" />
                </div>
                <h3 class="text-sm uppercase tracking-wider mb-1">Pants</h3>
                <p class="text-xs text-gray-400">From $150</p>
            </div>
            <div class="group cursor-pointer">
                <div class="aspect-[3/4] bg-gray-100 mb-4 overflow-hidden">
                    <img src={accessories} alt="Accessories" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500" />
                </div>
                <h3 class="text-sm uppercase tracking-wider mb-1">Accessories</h3>
                <p class="text-xs text-gray-400">From $45</p>
            </div>
        </div>
    </section>

    <!-- Bottom CTA -->
    <section class="w-full grid grid-cols-1 md:grid-cols-2 h-[600px]">
        <div class="relative group overflow-hidden">
            <img src={ctaShop} alt="Shop collection" class="w-full h-full object-cover transition-transform duration-700 group-hover:scale-105" />
            <div class="absolute inset-0 bg-black/30 group-hover:bg-black/40 transition-colors"></div>
            <div class="absolute inset-0 flex flex-col items-center justify-center text-white text-center p-6">
                <h2 class="font-display text-3xl md:text-4xl mb-2">Shop Collection</h2>
                <p class="text-sm font-light mb-8 opacity-90">Discover our premium golf essentials.</p>
                <button class="border border-white px-8 py-3 text-xs uppercase tracking-widest hover:bg-white hover:text-black transition-colors">
                    Explore Now
                </button>
            </div>
        </div>
        <div class="relative group overflow-hidden">
            <img src={ctaStory} alt="Our story" class="w-full h-full object-cover transition-transform duration-700 group-hover:scale-105" />
            <div class="absolute inset-0 bg-black/30 group-hover:bg-black/40 transition-colors"></div>
            <div class="absolute inset-0 flex flex-col items-center justify-center text-white text-center p-6">
                <h2 class="font-display text-3xl md:text-4xl mb-2">Our Story</h2>
                <p class="text-sm font-light mb-8 opacity-90">Learn about our philosophy and approach to modern golf style.</p>
                <button class="border border-white px-8 py-3 text-xs uppercase tracking-widest hover:bg-white hover:text-black transition-colors">
                    Read More
                </button>
            </div>
        </div>
    </section>
</div>
