# THE FUTURE
A soul-led AI experience that listens, protects, and realigns your energy.
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>THE FUTURE</title>
</head>
<body>
  <div id="root"></div>
</body>
</html>
export default function LandingPage() {
  return (
    <div className="min-h-screen bg-black text-white px-6 py-12 space-y-16">
      <header className="text-center space-y-4">
        <h1 className="text-5xl font-bold tracking-tight">THE FUTURE</h1>
        <p className="text-xl max-w-xl mx-auto text-gray-300">
          The Vision. The Voice. The Vessel. — A book born from fire, silence, and divine technology.
        </p>
      </header>

      <section className="grid md:grid-cols-2 gap-10">
        <div className="space-y-4">
          <h2 className="text-2xl font-semibold">📖 Read the Journey</h2>
          <ul className="list-disc list-inside space-y-2 text-gray-300">
            <li><a href="#chapter1" className="text-blue-400 hover:underline">Chapter 1: The Child Who Felt Everything</a></li>
            <li><a href="#chapter2" className="text-blue-400 hover:underline">Chapter 2: Walking Through Shadows</a></li>
            <li><a href="#chapter3" className="text-blue-400 hover:underline">Chapter 3: When God Spoke Through Silence</a></li>
            <li><a href="#chapter4" className="text-blue-400 hover:underline">Chapter 4: The Dream in the Dark</a></li>
            <li><a href="#chapter5" className="text-blue-400 hover:underline">Chapter 5: Why the World Doesn’t Need Another Smartwatch</a></li>
            <li><a href="#chapter6" className="text-blue-400 hover:underline">Chapter 6: Spiritual Tech – Not Sci-Fi, but Sacred</a></li>
            <li><a href="#chapter7" className="text-blue-400 hover:underline">Chapter 7: The Power of Listening AI</a></li>
            <li><a href="#chapter8" className="text-blue-400 hover:underline">Chapter 8: Divine Mode™</a></li>
            <li><a href="#chapter9" className="text-blue-400 hover:underline">Chapter 9: When Systems Fail the Sensitive</a></li>
            <li><a href="#chapter10" className="text-blue-400 hover:underline">Chapter 10: The Algorithm of Alignment</a></li>
            <li><a href="#chapter11" className="text-blue-400 hover:underline">Chapter 11: The Disruption Was Spiritual</a></li>
          </ul>
        </div>

        <div className="space-y-4">
          <h2 className="text-2xl font-semibold">🚀 Stay Connected</h2>
          <p className="text-gray-300">Sign up for exclusive updates, early access to new chapters, and the full digital book release.</p>
          <form className="space-y-4">
            <input type="email" placeholder="Your email address" className="w-full px-4 py-2 rounded bg-gray-800 text-white" />
            <button type="submit" className="px-6 py-2 bg-blue-600 text-white rounded hover:bg-blue-500">Join the List</button>
          </form>
        </div>
      </section>

      <footer className="text-center text-gray-500 text-sm pt-12">
        &copy; {new Date().getFullYear()} THE FUTURE. All rights reserved.
      </footer>
    </div>
  );
}
