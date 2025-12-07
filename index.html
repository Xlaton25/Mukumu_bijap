import React, { useState, useEffect } from 'react';
import { Camera, Film, Menu, X, Instagram, Mail, Phone, MapPin, Facebook, Youtube, ChevronRight, ArrowRight, MoreVertical } from 'lucide-react';

/**
 * MUKUMU BIJAP - Official Portfolio Website
 * * DESIGN PHILOSOPHY:
 * "The Digital Book" - The site is designed to feel like flipping through a high-end magazine.
 * Colors: Stone/Cream (Paper), Charcoal (Ink), and Gold (Premium).
 * Typography: Serif for Headings (Book feel), Sans-Serif for readability.
 */

// --- Components ---

const Section = ({ id, className, children }) => (
  <section id={id} className={`py-20 px-6 md:px-12 lg:px-24 ${className}`}>
    {children}
  </section>
);

const FadeIn = ({ children, delay = 0 }) => {
  const [isVisible, setIsVisible] = useState(false);
  const domRef = React.useRef();

  useEffect(() => {
    const observer = new IntersectionObserver(entries => {
      entries.forEach(entry => setIsVisible(entry.isIntersecting));
    });
    if (domRef.current) observer.observe(domRef.current);
    return () => observer.disconnect();
  }, []);

  return (
    <div
      ref={domRef}
      className={`transition-opacity duration-1000 transform translate-y-0 ${
        isVisible ? 'opacity-100 translate-y-0' : 'opacity-0 translate-y-10'
      }`}
      style={{ transitionDelay: `${delay}ms` }}
    >
      {children}
    </div>
  );
};

const PortfolioCard = ({ category, title, image, tags }) => (
  <div className="group relative overflow-hidden rounded-sm cursor-pointer shadow-sm hover:shadow-xl transition-all duration-300">
    <div className="aspect-[3/4] overflow-hidden bg-stone-200">
      <img 
        src={image} 
        alt={`${title} - Mukumu Bijap Photography`} 
        className="w-full h-full object-cover transition-transform duration-700 group-hover:scale-105"
        loading="lazy"
      />
    </div>
    <div className="absolute inset-0 bg-gradient-to-t from-stone-900/90 via-stone-900/20 to-transparent opacity-0 group-hover:opacity-100 transition-opacity duration-300 flex flex-col justify-end p-6">
      <span className="text-amber-400 text-xs font-bold tracking-widest uppercase mb-2">{category}</span>
      <h3 className="text-white text-xl font-serif">{title}</h3>
      <div className="flex gap-2 mt-3">
        {tags.map((tag, i) => (
          <span key={i} className="text-xs text-stone-300 border border-stone-600 px-2 py-1 rounded-full">{tag}</span>
        ))}
      </div>
    </div>
  </div>
);

const ServiceCard = ({ icon: Icon, title, desc, price }) => (
  <div className="bg-white p-8 border border-stone-100 hover:border-amber-200 transition-colors duration-300 rounded-sm shadow-sm">
    <Icon className="w-10 h-10 text-amber-600 mb-6" strokeWidth={1.5} />
    <h3 className="text-2xl font-serif text-stone-900 mb-4">{title}</h3>
    <p className="text-stone-600 mb-6 leading-relaxed">{desc}</p>
    <div className="flex items-center justify-between mt-auto">
      <span className="text-sm font-semibold text-stone-400">{price}</span>
      <button className="text-stone-900 hover:text-amber-600 font-medium flex items-center gap-2 text-sm transition-colors">
        View Details <ArrowRight size={16} />
      </button>
    </div>
  </div>
);

// --- Main App ---

export default function App() {
  const [isMenuOpen, setIsMenuOpen] = useState(false);
  const [scrolled, setScrolled] = useState(false);

  // Handle Scroll for Navbar styling
  useEffect(() => {
    const handleScroll = () => setScrolled(window.scrollY > 50);
    window.addEventListener('scroll', handleScroll);
    return () => window.removeEventListener('scroll', handleScroll);
  }, []);

  // SEO Head Configuration (Simulated)
  const MetaTags = () => (
    <div className="hidden">
      <title>Mukumu Bijap | Premium Photography & Film Agency Agartala</title>
      <meta name="description" content="Mukumu Bijap is Tripura's premier creative agency specializing in cinematic wedding films, commercial brand storytelling, and cultural documentation." />
      <meta name="keywords" content="Tripura Photography, Agartala Wedding Photographer, Mukumu Bijap, Cinematic Video Tripura, Commercial Photography Agartala" />
    </div>
  );

  return (
    <div className="bg-stone-50 min-h-screen font-sans text-stone-800 selection:bg-amber-200 selection:text-stone-900">
      <MetaTags />

      {/* --- Navigation --- */}
      <nav 
        className={`fixed top-0 left-0 right-0 z-50 transition-all duration-300 border-b ${
          scrolled || isMenuOpen ? 'bg-white border-stone-100 shadow-sm py-3' : 'bg-transparent border-transparent py-6'
        }`}
      >
        <div className="container mx-auto px-6 flex justify-between items-center relative z-50">
          
          {/* Brand Logo */}
          <div className="flex items-center gap-3">
            <div className={`w-10 h-10 rounded-full border-2 flex items-center justify-center transition-colors ${
              scrolled || isMenuOpen ? 'border-stone-900 text-stone-900' : 'border-white text-white'
            }`}>
              <Camera size={20} />
            </div>
            <span className={`font-serif text-xl md:text-2xl font-bold tracking-tight transition-colors ${
              scrolled || isMenuOpen ? 'text-stone-900' : 'text-white'
            }`}>
              MUKUMU BIJAP
            </span>
          </div>

          {/* Desktop Menu */}
          <div className={`hidden md:flex gap-8 text-sm font-medium tracking-wide ${scrolled ? 'text-stone-600' : 'text-stone-200'}`}>
            {['Portfolio', 'Services', 'Philosophy', 'Contact'].map((item) => (
              <a key={item} href={`#${item.toLowerCase()}`} className="hover:text-amber-500 transition-colors">
                {item.toUpperCase()}
              </a>
            ))}
          </div>

          {/* Mobile Menu Trigger (Ellipsis / Menu) */}
          <button 
            onClick={() => setIsMenuOpen(!isMenuOpen)} 
            className={`md:hidden p-2 rounded-full hover:bg-black/5 transition-colors ${
               scrolled || isMenuOpen ? 'text-stone-900' : 'text-white'
            }`}
            aria-label="Toggle Menu"
          >
            {isMenuOpen ? <X size={28} /> : <Menu size={28} />}
          </button>
        </div>

        {/* --- Mobile Fullscreen Menu (FIXED) --- */}
        <div 
          className={`fixed inset-0 bg-stone-50 z-40 flex flex-col px-6 pt-32 pb-10 transition-transform duration-500 ease-in-out ${
            isMenuOpen ? 'translate-x-0' : 'translate-x-full'
          }`}
          style={{ top: '0', height: '100vh', overflowY: 'auto' }}
        >
          <div className="flex flex-col gap-6 items-start">
             {/* Divider */}
            <div className="w-12 h-1 bg-amber-500 mb-4"></div>

            {['Portfolio', 'Services', 'Philosophy', 'Contact'].map((item, index) => (
              <a 
                key={item} 
                href={`#${item.toLowerCase()}`} 
                onClick={() => setIsMenuOpen(false)}
                className="text-4xl font-serif text-stone-900 hover:text-amber-600 transition-colors transform translate-x-0 active:scale-95 origin-left"
                style={{ transitionDelay: `${index * 50}ms` }}
              >
                {item}
              </a>
            ))}

            {/* Mobile Contact Info */}
            <div className="mt-auto pt-12 border-t border-stone-200 w-full">
                <p className="text-stone-500 text-sm uppercase tracking-widest mb-4">Get in touch</p>
                <div className="flex gap-6 text-stone-900 mb-4">
                    <Instagram size={24} />
                    <Facebook size={24} />
                    <Youtube size={24} />
                </div>
                <p className="text-stone-600 font-medium">+91 98765 43210</p>
                <p className="text-stone-600 text-sm">hello@mukumubijap.com</p>
            </div>
          </div>
        </div>
      </nav>

      {/* --- Hero Section --- */}
      <header id="home" className="relative h-screen w-full overflow-hidden flex items-center justify-center bg-stone-900">
        {/* Background Image / Video Placeholder */}
        <div className="absolute inset-0 opacity-60">
           {/* Replace this URL with a high-quality video or image of Tripura/Weddings */}
           <img 
            src="https://images.unsplash.com/photo-1511285560982-1351c4f809b9?q=80&w=2000&auto=format&fit=crop" 
            alt="Cinematic Wedding Photography Tripura" 
            className="w-full h-full object-cover"
           />
        </div>
        <div className="absolute inset-0 bg-black/40" />

        <div className="relative z-10 text-center px-4 max-w-4xl mx-auto mt-20">
          <p className="text-amber-400 text-sm md:text-base tracking-[0.3em] uppercase mb-4 font-medium animate-fade-in-up">
            Visual Publishing House • Agartala
          </p>
          <h1 className="text-5xl md:text-7xl lg:text-8xl font-serif text-white mb-6 leading-tight">
            Your Life,<br/> Unwritten.
          </h1>
          <p className="text-stone-200 text-lg md:text-xl max-w-2xl mx-auto mb-10 font-light">
            We don't just take photos. We author your visual legacy. From intimate weddings to grand commercial narratives.
          </p>
          <div className="flex flex-col md:flex-row gap-4 justify-center">
            <a href="#portfolio" className="bg-amber-600 hover:bg-amber-700 text-white px-8 py-4 rounded-sm font-medium transition-all tracking-wide">
              View Our Work
            </a>
            <a href="#contact" className="border border-white/30 hover:bg-white hover:text-stone-900 text-white px-8 py-4 rounded-sm font-medium transition-all tracking-wide backdrop-blur-sm">
              Book a Session
            </a>
          </div>
        </div>
      </header>

      {/* --- Philosophy / About (Brand Story) --- */}
      <Section id="philosophy" className="bg-stone-50">
        <div className="max-w-3xl mx-auto text-center">
          <FadeIn>
            <h2 className="text-3xl md:text-4xl font-serif text-stone-900 mb-6">The Meaning of Mukumu Bijap</h2>
            <div className="w-24 h-1 bg-amber-600 mx-auto mb-8"></div>
            <p className="text-lg text-stone-600 leading-relaxed mb-6">
              In the heart of our heritage, <strong>'Mukumu'</strong> whispers of culture and tradition, while <strong>'Bijap'</strong> signifies a book.
            </p>
            <p className="text-lg text-stone-600 leading-relaxed">
              We founded this agency on a simple yet profound belief: 
              <span className="italic text-stone-800"> Every person carries a story worthy of a book.</span>
              Whether it is the timeless rituals of a Tripuri wedding, the fast-paced energy of a corporate brand, or the quiet portrait of an artist, 
              we act as the authors of your visual history. We are not just photographers; we are archivists of the present.
            </p>
          </FadeIn>
        </div>
      </Section>

      {/* --- Portfolio Section --- */}
      <Section id="portfolio" className="bg-white">
        <div className="flex flex-col md:flex-row justify-between items-end mb-12">
          <div>
            <span className="text-amber-600 font-bold tracking-widest text-sm uppercase">Curated Gallery</span>
            <h2 className="text-4xl font-serif text-stone-900 mt-2">Selected Works</h2>
          </div>
          <a href="#" className="hidden md:flex items-center gap-2 text-stone-500 hover:text-amber-600 transition-colors mt-4 md:mt-0">
            View Full Archive <ArrowRight size={18}/>
          </a>
        </div>

        <div className="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
          <PortfolioCard 
            category="The Wedding Chapter"
            title="Siyari & Rohan"
            image="https://images.unsplash.com/photo-1606216794074-735e91aa2c92?q=80&w=800&auto=format&fit=crop"
            tags={['Cinematic', 'Traditional', 'Agartala']}
          />
          <PortfolioCard 
            category="Commercial"
            title="Handloom Heritage"
            image="https://images.unsplash.com/photo-1452800185063-6db5e12b8e2e?q=80&w=800&auto=format&fit=crop"
            tags={['Brand', 'Fashion', 'Risa']}
          />
          <PortfolioCard 
            category="Editorial"
            title="Hukumu Festival"
            image="https://images.unsplash.com/photo-1533158676154-1b3293dc747b?q=80&w=800&auto=format&fit=crop"
            tags={['Culture', 'Event', 'Documentary']}
          />
           <PortfolioCard 
            category="The Wedding Chapter"
            title="Debbarma Nuptials"
            image="https://images.unsplash.com/photo-1583939003024-3027dc1a994a?q=80&w=800&auto=format&fit=crop"
            tags={['Candid', 'Bridal', 'Udaipur']}
          />
           <PortfolioCard 
            category="Music Video"
            title="Echoes of the Hills"
            image="https://images.unsplash.com/photo-1516280440614-6697288d5d38?q=80&w=800&auto=format&fit=crop"
            tags={['Production', 'Music', '4K']}
          />
           <PortfolioCard 
            category="Portraits"
            title="Modern Identity"
            image="https://images.unsplash.com/photo-1534528741775-53994a69daeb?q=80&w=800&auto=format&fit=crop"
            tags={['Studio', 'Headshots', 'Lighting']}
          />
        </div>
        
        <div className="mt-12 text-center md:hidden">
          <a href="#" className="inline-flex items-center gap-2 text-stone-900 border-b border-stone-900 pb-1">
            View Full Archive <ArrowRight size={18}/>
          </a>
        </div>
      </Section>

      {/* --- Services Section --- */}
      <Section id="services" className="bg-stone-100">
        <div className="text-center max-w-2xl mx-auto mb-16">
          <h2 className="text-4xl font-serif text-stone-900 mb-4">Our Expertise</h2>
          <p className="text-stone-600">
            We offer bespoke packages tailored to the unique needs of weddings, brands, and artists.
          </p>
        </div>

        <div className="grid grid-cols-1 md:grid-cols-3 gap-8">
          <ServiceCard 
            icon={Camera}
            title="Wedding Chronicles"
            desc="Complete coverage of your special days. Includes Pre-wedding conceptual shoots, Cinematic Wedding Films (Teasers + Full Length), and Candid Photography. We understand the nuances of Tripuri, Bengali, and Christian traditions."
            price="Starting at ₹45,000"
          />
          <ServiceCard 
            icon={Film}
            title="Commercial & Brand"
            desc="Elevate your business with high-end visuals. We produce Product Commercials, Real Estate Walkthroughs, Food Photography for Cafes, and Corporate Event Highlights designed for social media growth."
            price="Custom Quotes"
          />
          <ServiceCard 
            icon={Instagram}
            title="Digital Content"
            desc="For influencers, musicians, and artists. We create Music Videos, Reels Packages, and High-Fashion Portfolios that define your personal brand."
            price="Hourly / Project Basis"
          />
        </div>
      </Section>

      {/* --- Stats / Trust Indicators --- */}
      <section className="bg-stone-900 py-16 text-white border-y border-stone-800">
        <div className="container mx-auto px-6 grid grid-cols-2 md:grid-cols-4 gap-8 text-center">
          <div>
            <div className="text-4xl font-serif text-amber-500 mb-2">150+</div>
            <div className="text-sm tracking-widest uppercase text-stone-400">Weddings Documented</div>
          </div>
          <div>
            <div className="text-4xl font-serif text-amber-500 mb-2">50+</div>
            <div className="text-sm tracking-widest uppercase text-stone-400">Commercial Projects</div>
          </div>
          <div>
            <div className="text-4xl font-serif text-amber-500 mb-2">4K</div>
            <div className="text-sm tracking-widest uppercase text-stone-400">Resolution Standard</div>
          </div>
          <div>
            <div className="text-4xl font-serif text-amber-500 mb-2">100%</div>
            <div className="text-sm tracking-widest uppercase text-stone-400">Client Satisfaction</div>
          </div>
        </div>
      </section>

      {/* --- Contact Section --- */}
      <Section id="contact" className="bg-white">
        <div className="grid grid-cols-1 lg:grid-cols-2 gap-16">
          {/* Contact Info */}
          <div>
            <h2 className="text-4xl font-serif text-stone-900 mb-6">Let's Write Your Story</h2>
            <p className="text-stone-600 mb-10 text-lg">
              We are currently accepting bookings for the 2025-2026 wedding season and commercial projects in Tripura & Northeast India.
            </p>
            
            <div className="space-y-6">
              <div className="flex items-start gap-4">
                <div className="bg-amber-100 p-3 rounded-full text-amber-700">
                  <Phone size={20} />
                </div>
                <div>
                  <h4 className="font-bold text-stone-900">Call Us</h4>
                  <p className="text-stone-600">+91 98765 43210 (Booking Desk)</p>
                </div>
              </div>

              <div className="flex items-start gap-4">
                <div className="bg-amber-100 p-3 rounded-full text-amber-700">
                  <Mail size={20} />
                </div>
                <div>
                  <h4 className="font-bold text-stone-900">Email</h4>
                  <p className="text-stone-600">hello@mukumubijap.com</p>
                </div>
              </div>

              <div className="flex items-start gap-4">
                <div className="bg-amber-100 p-3 rounded-full text-amber-700">
                  <MapPin size={20} />
                </div>
                <div>
                  <h4 className="font-bold text-stone-900">Studio</h4>
                  <p className="text-stone-600">Krishnanagar, Agartala, Tripura - 799001</p>
                </div>
              </div>
            </div>

            <div className="mt-10 flex gap-4">
              <a href="#" className="p-3 bg-stone-100 rounded-full hover:bg-amber-600 hover:text-white transition-all"><Instagram size={20}/></a>
              <a href="#" className="p-3 bg-stone-100 rounded-full hover:bg-blue-600 hover:text-white transition-all"><Facebook size={20}/></a>
              <a href="#" className="p-3 bg-stone-100 rounded-full hover:bg-red-600 hover:text-white transition-all"><Youtube size={20}/></a>
            </div>
          </div>

          {/* Contact Form */}
          <div className="bg-stone-50 p-8 rounded-lg border border-stone-200 shadow-sm">
            <form className="space-y-6">
              <div className="grid grid-cols-1 md:grid-cols-2 gap-6">
                <div>
                  <label className="block text-xs font-bold uppercase tracking-wide text-stone-500 mb-2">Name</label>
                  <input type="text" className="w-full bg-white border border-stone-300 p-3 rounded-sm focus:outline-none focus:border-amber-500 transition-colors" placeholder="Your Name" />
                </div>
                <div>
                  <label className="block text-xs font-bold uppercase tracking-wide text-stone-500 mb-2">Phone</label>
                  <input type="tel" className="w-full bg-white border border-stone-300 p-3 rounded-sm focus:outline-none focus:border-amber-500 transition-colors" placeholder="+91" />
                </div>
              </div>
              
              <div>
                <label className="block text-xs font-bold uppercase tracking-wide text-stone-500 mb-2">Event Type</label>
                <select className="w-full bg-white border border-stone-300 p-3 rounded-sm focus:outlin
