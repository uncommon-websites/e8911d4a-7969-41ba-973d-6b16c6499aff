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



<div class="w-full">
    <!-- Hero Section -->
    <section class="w-full mb-16 md:mb-24 px-4 md:px-6 max-w-[1600px] mx-auto">
        <div class="relative w-full aspect-[16/9] md:aspect-[21/9] overflow-hidden">
            <img src={heroImage} alt="Kent Avenue Penthouse" class="w-full h-full object-cover" />
            <button class="absolute bottom-6 right-6 bg-transparent border border-white/50 text-white px-4 py-2 text-xs uppercase tracking-widest hover:bg-white hover:text-black transition-colors flex items-center gap-2">
                Share
                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-4 h-4">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M3.75 3.75v4.5m0-4.5h4.5m-4.5 0L9 9M3.75 20.25v-4.5m0 4.5h4.5m-4.5 0L9 15M20.25 3.75h-4.5m4.5 0v4.5m0-4.5L15 9m5.25 11.25h-4.5m4.5 0v-4.5m0 4.5L15 15" />
                </svg>
            </button>
        </div>
    </section>

    <!-- Project Info -->
    <section class="max-w-[1200px] mx-auto px-6 mb-24 md:mb-32">
        <div class="grid grid-cols-1 md:grid-cols-2 gap-12 md:gap-24">
            <div>
                <h1 class="font-display text-4xl md:text-5xl text-gray-900 mb-8">Kent Avenue Penthouse</h1>
                <div class="text-gray-600 text-sm leading-relaxed space-y-4 max-w-md font-light">
                    <p>
                        Perched high above the bustling city of New York, with magnificent views of the East River and the iconic Manhattan skyline, this unique penthouse flat combines warm minimalism and tactile materiality.
                    </p>
                    <p>
                        The flat, which was designed and decorated by Norm Architects, strikes a perfect balance between New York's raw industrial vibe and a timeless Scandinavian aesthetic.
                    </p>
                </div>
            </div>
            <div class="grid grid-cols-2 gap-y-6 text-[11px] uppercase tracking-wider">
                <div class="text-gray-400">Private residence</div>
                <div class="text-gray-900">New York City, USA</div>

                <div class="text-gray-400">Architect</div>
                <div class="text-gray-900">Norm Architects</div>

                <div class="text-gray-400">Photographer</div>
                <div class="text-gray-900">Jonas Bjerre-Poulsen</div>

                <div class="col-span-2 pt-6 border-t border-gray-100 mt-2">
                    <div class="text-gray-400 mb-1">Product</div>
                    <div class="text-gray-900">Dinesen HeartOak, Natural Oil, Dinesen Collection</div>
                </div>
            </div>
        </div>
    </section>

    <!-- Image Grid 1 -->
    <section class="max-w-[1600px] mx-auto px-6 mb-24 md:mb-32">
        <div class="grid grid-cols-1 md:grid-cols-12 gap-6 items-start">
            <div class="md:col-span-5 md:col-start-2">
                <img src={deskImage} alt="Desk detail" class="w-full aspect-[3/4] object-cover mb-4" />
                <p class="text-xs text-gray-400 font-light max-w-xs mt-8 leading-relaxed">
                    The dwelling was designed to provide a calm refuge from the hectic pulse of the city, with a minimalist interior that combines warm, functional and aesthetic qualities to create a solving and harmonious setting.
                </p>
            </div>
            <div class="md:col-span-5 md:col-start-8 md:mt-32">
                 <img src={glassesImage} alt="Glasses detail" class="w-full aspect-square object-cover" />
            </div>
        </div>
    </section>

    <!-- Full Width Image -->
    <section class="max-w-[1600px] mx-auto px-6 mb-24 md:mb-32">
        <img src={bedroomImage} alt="Bedroom view" class="w-full aspect-[16/9] md:aspect-[21/9] object-cover" />
    </section>

    <!-- Image Grid 2 -->
    <section class="max-w-[1600px] mx-auto px-6 mb-24 md:mb-32">
        <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
            <div>
                <img src={bedCornerImage} alt="Bedroom corner" class="w-full aspect-[3/4] object-cover" />
            </div>
            <div class="flex flex-col justify-between">
                <img src={woodDetailImage} alt="Wood detail" class="w-full aspect-[3/4] object-cover mb-8" />
                <div class="max-w-xs ml-auto">
                     <p class="text-xs text-gray-400 font-light leading-relaxed">
                        Dinesen Oak plays a central role in the bespoke solutions that define the interior. The timeless quality of the wood is highlighted in custom-made features designed to match the feel and functions of the flat. These specially designed elements include a bedframe, a wardrobe, a shelving unit and an integrated desk, all made of Dinesen Oak, which adds a warm and organic touch to the space.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- Image Grid 3 -->
    <section class="max-w-[1600px] mx-auto px-6 mb-24 md:mb-32">
        <div class="grid grid-cols-1 md:grid-cols-12 gap-6 items-end">
             <div class="md:col-span-5">
                <img src={shelfDetailImage} alt="Shelf detail" class="w-full aspect-[4/5] object-cover" />
            </div>
            <div class="md:col-span-7">
                <img src={shelfFullImage} alt="Shelf full view" class="w-full aspect-[4/3] object-cover" />
            </div>
        </div>
    </section>

    <!-- Large Living Room Image -->
    <section class="w-full mb-24 md:mb-32">
        <img src={livingRoomImage} alt="Living room" class="w-full h-[80vh] object-cover" />
    </section>

    <!-- Image Grid 4 & Text -->
    <section class="max-w-[1600px] mx-auto px-6 mb-24 md:mb-32">
        <div class="grid grid-cols-1 md:grid-cols-2 gap-6 mb-16 items-start">
            <img src={hallwayImage} alt="Hallway" class="w-full aspect-[3/4] object-cover" />
            <div class="md:pt-32">
                 <img src={kitchenImage} alt="Kitchen detail" class="w-full aspect-[3/4] object-cover" />
            </div>
        </div>
        <div class="flex justify-end">
             <p class="text-xs text-gray-400 font-light max-w-md leading-relaxed">
                The tactile materials selected for the interior solutions create an experience that elevates the design from being merely visual into a strong sensuous impact. Every element of the interior was carefully selected to support the calm and harmonious atmosphere. Dinesen Oak make a contribution that is not just aesthetic but also functional as the natural and durable materials blend perfectly into Norm Architects' stringent and simple design expression.
            </p>
        </div>
    </section>

    <!-- Terrace Image -->
    <section class="w-full mb-24 md:mb-32">
        <img src={terraceImage} alt="Terrace" class="w-full h-[70vh] object-cover" />
    </section>

    <!-- Bottom Text -->
    <section class="max-w-[1600px] mx-auto px-6 mb-24 md:mb-32">
        <div class="max-w-md">
            <p class="text-xs text-gray-400 font-light leading-relaxed">
                With a high priority on the sourcing of materials and a keen eye for details, Norm Architects demonstrate their dedication to quality and timeless design in their design of Kent Avenue Penthouse. The result is a dwelling where aesthetic and functional qualities come together in a harmonious, modern and luxurious space - a genuine tribute to natural materials and their ability to ennoble calm in an otherwise hectic world.
            </p>
        </div>
    </section>

    <!-- Final Grid -->
    <section class="max-w-[1600px] mx-auto px-6 mb-32 md:mb-40">
        <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
            <img src={woodJoineryImage} alt="Wood joinery" class="w-full aspect-[3/4] object-cover" />
            <div class="pt-20">
                <img src={kitchenIslandImage} alt="Kitchen island" class="w-full aspect-[3/4] object-cover" />
            </div>
        </div>
    </section>

    <!-- Share Section -->
    <section class="max-w-[1600px] mx-auto px-6 mb-32">
        <h3 class="font-display text-2xl mb-6">Share</h3>
        <div class="flex gap-6 text-xs text-gray-400 uppercase tracking-wide">
            <a href="#" class="hover:text-black transition-colors">Pinterest</a>
            <a href="#" class="hover:text-black transition-colors">Twitter</a>
            <a href="#" class="hover:text-black transition-colors">E-mail</a>
            <a href="#" class="hover:text-black transition-colors">LinkedIn</a>
            <a href="#" class="hover:text-black transition-colors">Facebook</a>
        </div>
    </section>

    <!-- Bottom CTA -->
    <section class="w-full grid grid-cols-1 md:grid-cols-2 h-[600px]">
        <div class="relative group overflow-hidden">
            <img src={ctaLeft} alt="Get inspired" class="w-full h-full object-cover transition-transform duration-700 group-hover:scale-105" />
            <div class="absolute inset-0 bg-black/20 group-hover:bg-black/30 transition-colors"></div>
            <div class="absolute inset-0 flex flex-col items-center justify-center text-white text-center p-6">
                <h2 class="font-display text-3xl md:text-4xl mb-2">Get inspired</h2>
                <p class="text-sm font-light mb-8 opacity-90">Explore our many projects from around the world.</p>
                <button class="border border-white px-8 py-3 text-xs uppercase tracking-widest hover:bg-white hover:text-black transition-colors">
                    Order Cases
                </button>
            </div>
        </div>
        <div class="relative group overflow-hidden">
            <img src={ctaRight} alt="Price Lists" class="w-full h-full object-cover transition-transform duration-700 group-hover:scale-105" />
            <div class="absolute inset-0 bg-black/20 group-hover:bg-black/30 transition-colors"></div>
            <div class="absolute inset-0 flex flex-col items-center justify-center text-white text-center p-6">
                <h2 class="font-display text-3xl md:text-4xl mb-2">Receive Dinesen Price Lists</h2>
                <p class="text-sm font-light mb-8 opacity-90">A Dinesen floor sprouts in the dream, but grows from reality.</p>
                <button class="border border-white px-8 py-3 text-xs uppercase tracking-widest hover:bg-white hover:text-black transition-colors">
                    Explore
                </button>
            </div>
        </div>
    </section>
</div>

