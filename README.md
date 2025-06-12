# Tierra-Verde
Cacti Business
tierra-verde-site/
import Image from "next/image";
import logo from "./logo-tierra-verde.png";

export default function TierraVerde() {
  return (
    <main className="min-h-screen bg-[#f4e4d5] text-[#4b2e1c] font-serif">
      {/* Hero Section */}
      <section className="text-center py-20 px-4 bg-[#d6a77a]">
        <div className="flex justify-center mb-6">
          <Image src={logo} alt="Tierra Verde Logo" width={100} height={100} />
        </div>
        <h1 className="text-5xl font-bold mb-4 tracking-wide">Tierra Verde</h1>
        <p className="text-xl mb-6 italic">Rooted in the Earth. Raised by the Sun.</p>
        <div className="space-x-4">
          <button className="bg-[#4b2e1c] text-white px-6 py-2 rounded-full shadow-md">Shop Now</button>
          <button className="border border-[#4b2e1c] px-6 py-2 rounded-full">Trade Discounts</button>
        </div>
      </section>

      {/* About Section */}
      <section className="py-16 px-6 max-w-3xl mx-auto">
        <h2 className="text-3xl font-bold mb-4">Our Story</h2>
        <p className="mb-4 text-lg">
          Tierra Verde was born from a love of desert landscapes, ancient clay traditions, and the towering silhouettes of giant cacti. Based in South Africa, we source exceptional large cacti and create handmade clay pots that are as natural as the soil they come from. Every piece is grounded in authenticity, crafted slowly, and designed to be lived with.
        </p>
        <p className="text-lg">
          Our pieces bring the desert’s quiet magic into homes, gardens, and spaces that celebrate the connection between the wild and the cultivated.
        </p>
        <p className="text-lg mt-4">
          While we sell exclusively to end users, we do offer discounts for trade professionals such as interior designers, landscapers, and specialty stores.
        </p>
      </section>

      {/* Shop Section */}
      <section className="bg-[#e9d6c3] py-16 px-6">
        <h2 className="text-3xl font-bold mb-8 text-center">Shop</h2>
        <div className="grid grid-cols-1 md:grid-cols-3 gap-8 max-w-6xl mx-auto">
          <div className="bg-white rounded-2xl shadow p-6 text-center">
            <h3 className="text-xl font-semibold mb-2">XXL Cacti</h3>
            <p>Rare, towering specimens up to 2m high.</p>
          </div>
          <div className="bg-white rounded-2xl shadow p-6 text-center">
            <h3 className="text-xl font-semibold mb-2">Clay Pots</h3>
            <p>Handmade, stamp-branded, earthy vessels for your plants.</p>
          </div>
          <div className="bg-white rounded-2xl shadow p-6 text-center">
            <h3 className="text-xl font-semibold mb-2">Cactus + Pot Sets</h3>
            <p>Curated combinations, rooted in harmony.</p>
          </div>
        </div>
      </section>

      {/* Journal Section */}
      <section className="py-16 px-6 max-w-4xl mx-auto">
        <h2 className="text-3xl font-bold mb-6">From the Journal</h2>
        <ul className="space-y-4">
          <li className="border-l-4 border-[#4b2e1c] pl-4">
            <h4 className="font-semibold">Caring for Giant Cacti</h4>
            <p className="text-sm text-gray-600">Simple tips for thriving desert giants.</p>
          </li>
          <li className="border-l-4 border-[#4b2e1c] pl-4">
            <h4 className="font-semibold">The Art of Clay</h4>
            <p className="text-sm text-gray-600">Behind the process of handcrafting each vessel.</p>
          </li>
          <li className="border-l-4 border-[#4b2e1c] pl-4">
            <h4 className="font-semibold">Designing with Desert Plants</h4>
            <p className="text-sm text-gray-600">Inspiration from minimalist desert gardens.</p>
          </li>
        </ul>
      </section>

      {/* Contact Section */}
      <section className="bg-[#d1a97e] py-16 px-6 text-center">
        <h2 className="text-3xl font-bold mb-4">Get in Touch</h2>
        <p className="mb-6">Custom orders, collaborations, or trade inquiries? We’d love to hear from you.</p>
        <form className="max-w-md mx-auto space-y-4">
          <input className="w-full px-4 py-2 rounded-lg border" type="text" placeholder="Your Name" />
          <input className="w-full px-4 py-2 rounded-lg border" type="email" placeholder="Your Email" />
          <textarea className="w-full px-4 py-2 rounded-lg border" rows="4" placeholder="Your Message" />
          <button className="bg-[#4b2e1c] text-white px-6 py-2 rounded-full shadow">Send</button>
        </form>
      </section>

      {/* Footer */}
      <footer className="text-center py-6 text-sm text-[#4b2e1c]">
        © {new Date().getFullYear()} Tierra Verde. Rooted in Earth.
      </footer>
    </main>
  );
}

