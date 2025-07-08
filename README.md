# Bengali-threads
export default function HomePage() { return ( <div className="min-h-screen bg-beige-100 text-brown-900 font-serif"> {/* Header */} <header className="p-6 shadow-md bg-white flex justify-between items-center"> <h1 className="text-3xl font-bold">Bengali Threads</h1> <nav className="space-x-4"> <a href="#home" className="hover:underline">Home</a> <a href="#about" className="hover:underline">About</a> <a href="#shop" className="hover:underline">Shop</a> <a href="#lookbook" className="hover:underline">Lookbook</a> <a href="#contact" className="hover:underline">Contact</a> </nav> </header>

{/* Hero Section */}
  <section id="home" className="p-10 text-center bg-beige-200">
    <h2 className="text-4xl font-bold mb-4">Celebrate Tradition with Elegance</h2>
    <p className="mb-6 max-w-xl mx-auto">
      Bengali Threads brings you handpicked traditional wear that reflects the essence of Bengal’s cultural heritage.
    </p>
    <Button className="bg-brown-800 text-white">Explore Collection</Button>
  </section>

  {/* About Section */}
  <section id="about" className="p-10 bg-white">
    <h3 className="text-2xl font-bold mb-4">About Us</h3>
    <p className="max-w-2xl">
      Bengali Threads is dedicated to preserving the timeless art of Bengali traditional clothing. Each piece is handcrafted with care, weaving stories of elegance, grace, and heritage.
    </p>
  </section>

  {/* Shop Section */}
  <section id="shop" className="p-10 bg-beige-100">
    <h3 className="text-2xl font-bold mb-6">Our Products</h3>
    <div className="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 gap-6">
      {[1, 2, 3].map((item) => (
        <Card key={item} className="bg-white shadow-md">
          <CardContent className="p-4">
            <div className="h-48 bg-beige-300 mb-4"></div>
            <h4 className="font-semibold">Product Name</h4>
            <p className="text-sm">Traditional attire description here</p>
            <Button className="mt-2 bg-brown-800 text-white">Buy Now</Button>
          </CardContent>

