export default function PortfolioApp() {
  const activities = [
    '2026-05-20','2026-05-21','2026-05-22','2026-05-25','2026-05-26','2026-05-27','2026-05-28','2026-05-29',
    '2026-06-01','2026-06-02','2026-06-03','2026-06-04','2026-06-05','2026-06-08','2026-06-09','2026-06-10',
    '2026-06-11','2026-06-12','2026-06-15','2026-06-16','2026-06-17','2026-06-18','2026-06-19','2026-06-22',
    '2026-06-23','2026-06-24','2026-06-25','2026-06-26','2026-06-29','2026-06-30'
  ];

  return (
    <div className="min-h-screen bg-slate-100 text-slate-800 font-sans">
      <header className="bg-slate-950 text-white shadow-lg sticky top-0 z-50 border-b border-slate-800">
        <div className="max-w-7xl mx-auto flex justify-between items-center px-6 py-4">
          <h1 className="text-2xl font-bold tracking-wide">MAHIMA SARA JACOB</h1>

          <nav className="space-x-6 text-sm md:text-base hidden md:flex">
            <a href="#home" className="hover:text-cyan-300 transition">Home</a>
            <a href="#tracker" className="hover:text-cyan-300 transition">PM Vikas Tracker</a>
            <a href="#contact" className="hover:text-cyan-300 transition">Contact</a>
          </nav>
        </div>
      </header>

      {/* PAGE 1 */}
      <section
        id="home"
        className="relative overflow-hidden bg-gradient-to-br from-slate-950 via-slate-900 to-cyan-950 text-white"
      >
        <div className="absolute inset-0 opacity-10 bg-[radial-gradient(circle_at_top_right,_white,_transparent_40%)]"></div>

        <div className="max-w-7xl mx-auto px-6 py-20 relative z-10">
          <div className="grid lg:grid-cols-2 gap-12 items-center min-h-[85vh]">
            <div>
              <div className="inline-block bg-cyan-500/20 border border-cyan-400/30 text-cyan-200 px-5 py-2 rounded-full text-sm mb-6 backdrop-blur-md">
                Electronics & Communication Engineering Student
              </div>

              <h1 className="text-5xl md:text-7xl font-black leading-tight mb-6">
                MAHIMA <span className="text-cyan-400">SARA</span> JACOB
              </h1>

              <p className="text-lg md:text-xl text-slate-300 leading-relaxed max-w-2xl mb-8">
                Passionate about IoT innovation, embedded systems, smart technologies, and engineering solutions.
                Currently pursuing B.Tech at College of Engineering Kidangoor and interning at IIIT Kottayam as an IoT Assistant.
              </p>

              <div className="flex flex-wrap gap-4">
                <a
                  href="#contact"
                  className="bg-cyan-500 hover:bg-cyan-400 text-slate-900 px-8 py-4 rounded-2xl font-semibold transition shadow-xl"
                >
                  Contact Me
                </a>

                <a
                  href="#tracker"
                  className="border border-slate-500 hover:border-cyan-400 hover:bg-cyan-500/10 px-8 py-4 rounded-2xl font-semibold transition"
                >
                  View PM Vikas Tracker
                </a>
              </div>
            </div>

            <div className="relative">
              <div className="bg-white/10 backdrop-blur-xl border border-white/10 rounded-[2rem] p-8 shadow-2xl">
                <div className="grid grid-cols-2 gap-6">
                  <div className="bg-slate-800/70 rounded-2xl p-6">
                    <h3 className="text-cyan-400 text-4xl font-bold">IoT</h3>
                    <p className="text-slate-300 mt-2">Technology Enthusiast</p>
                  </div>

                  <div className="bg-slate-800/70 rounded-2xl p-6">
                    <h3 className="text-cyan-400 text-4xl font-bold">ECE</h3>
                    <p className="text-slate-300 mt-2">Engineering Student</p>
                  </div>

                  <div className="bg-slate-800/70 rounded-2xl p-6 col-span-2">
                    <h3 className="text-2xl font-bold mb-3">Current Internship</h3>
                    <p className="text-slate-300 leading-relaxed">
                      Working at IIIT Kottayam on IoT Assistant projects involving smart systems,
                      embedded applications, and innovative technology solutions.
                    </p>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>

        <div className="bg-slate-100 text-slate-900 rounded-t-[3rem] relative z-20">
          <div className="max-w-7xl mx-auto px-6 py-20 space-y-14">
            <div className="grid lg:grid-cols-2 gap-10">
              <div className="bg-white rounded-[2rem] shadow-xl p-10 border border-slate-200 hover:-translate-y-1 transition duration-300">
                <h2 className="text-3xl font-bold mb-6 text-slate-900">About Me</h2>

                <p className="text-slate-600 leading-relaxed text-lg">
                  I am a highly motivated Electronics and Communication Engineering student
                  with a strong passion for Internet of Things, embedded systems,
                  communication technologies, and modern engineering innovation.
                </p>
              </div>

              <div className="bg-gradient-to-br from-cyan-600 to-slate-900 rounded-[2rem] shadow-2xl p-10 text-white">
                <h2 className="text-3xl font-bold mb-6">Education</h2>

                <div className="bg-white/10 rounded-2xl p-6 backdrop-blur-md border border-white/10">
                  <h3 className="text-2xl font-semibold">College of Engineering Kidangoor</h3>
                  <p className="text-cyan-100 mt-2">B.Tech in Electronics & Communication Engineering</p>
                  <p className="text-slate-200 mt-1">Kottayam, Kerala</p>
                </div>
              </div>
            </div>

            <div className="grid lg:grid-cols-2 gap-10">
              <div className="bg-white rounded-[2rem] shadow-xl p-10 border border-slate-200">
                <h2 className="text-3xl font-bold mb-6">Technical Skills</h2>

                <div className="flex flex-wrap gap-4">
                  {[
                    'IoT',
                    'Arduino',
                    'Embedded Systems',
                    'C Programming',
                    'Python',
                    'React',
                    'HTML/CSS',
                    'Communication Systems'
                  ].map((skill) => (
                    <span
                      key={skill}
                      className="bg-gradient-to-r from-cyan-100 to-cyan-50 text-cyan-900 px-5 py-3 rounded-2xl font-medium shadow-sm border border-cyan-200"
                    >
                      {skill}
                    </span>
                  ))}
                </div>
              </div>

              <div className="bg-white rounded-[2rem] shadow-xl p-10 border border-slate-200">
                <h2 className="text-3xl font-bold mb-6">Achievements</h2>

                <div className="space-y-5">
                  <div className="border-l-4 border-cyan-500 pl-5">
                    <h3 className="font-semibold text-lg">Selected for IIIT Kottayam Internship</h3>
                    <p className="text-slate-600 mt-1">
                      Chosen as an IoT Assistant Intern for technical learning and project exposure.
                    </p>
                  </div>

                  <div className="border-l-4 border-cyan-500 pl-5">
                    <h3 className="font-semibold text-lg">Engineering Project Participation</h3>
                    <p className="text-slate-600 mt-1">
                      Actively involved in practical electronics and communication mini projects.
                    </p>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>

      {/* PAGE 2 */}
      <section id="tracker" className="bg-slate-200 py-16 px-6">
        <div className="max-w-7xl mx-auto">
          <div className="text-center mb-10">
            <h2 className="text-4xl font-bold text-slate-800">PM Vikas Activity Tracker</h2>
            <p className="text-slate-600 mt-3">
              Track daily internship activities and upload supporting images.
            </p>
          </div>

          <div className="grid gap-6">
            {activities.map((date, index) => (
              <div
                key={index}
                className="bg-white rounded-2xl shadow-md p-6 border border-slate-200"
              >
                <div className="flex flex-col md:flex-row md:justify-between md:items-center gap-4 mb-4">
                  <div>
                    <h3 className="text-xl font-bold text-cyan-700">
                      Activity {index + 1}
                    </h3>
                    <p className="text-slate-500">Date: {date}</p>
                  </div>

                  <select className="border rounded-lg px-4 py-2 focus:outline-none focus:ring-2 focus:ring-cyan-500">
                    <option>Pending</option>
                    <option>Completed</option>
                    <option>In Progress</option>
                  </select>
                </div>

                <textarea
                  placeholder="Add activity notes here..."
                  className="w-full border rounded-xl p-4 min-h-[100px] focus:outline-none focus:ring-2 focus:ring-cyan-500"
                />

                <div className="mt-4 flex flex-col md:flex-row gap-4 items-start md:items-center">
                  <input
                    type="file"
                    className="border rounded-lg p-2 bg-slate-50"
                  />

                  <button className="bg-cyan-700 hover:bg-cyan-800 text-white px-6 py-2 rounded-lg transition">
                    Add Activity
                  </button>
                </div>
              </div>
            ))}
          </div>
        </div>
      </section>

      {/* PAGE 3 */}
      <section id="contact" className="max-w-5xl mx-auto px-6 py-16">
        <div className="bg-white rounded-3xl shadow-2xl p-10 text-center">
          <h2 className="text-4xl font-bold text-slate-800 mb-6">Resume & Contact</h2>

          <p className="text-slate-600 max-w-2xl mx-auto mb-8">
            Feel free to connect for internships, academic collaborations,
            and technology-related opportunities.
          </p>

          <div className="flex flex-col md:flex-row justify-center gap-6 mb-10">
            <a
              href="mailto:mahimasj07@gmail.com"
              className="bg-cyan-700 hover:bg-cyan-800 text-white px-6 py-3 rounded-xl shadow-md transition"
            >
              Email Me
            </a>

            <a
              href="#"
              className="border border-cyan-700 text-cyan-700 hover:bg-cyan-50 px-6 py-3 rounded-xl transition"
              download
            >
              Download Resume
            </a>
          </div>

          <div className="grid md:grid-cols-3 gap-6 text-left">
            <div className="bg-slate-100 rounded-2xl p-6">
              <h3 className="font-bold text-lg mb-2">Email</h3>
              <p className="text-slate-600">mahimasj07@gmail.com</p>
            </div>

            <div className="bg-slate-100 rounded-2xl p-6">
              <h3 className="font-bold text-lg mb-2">LinkedIn</h3>
              <p className="text-slate-600">Add LinkedIn Profile</p>
            </div>

            <div className="bg-slate-100 rounded-2xl p-6">
              <h3 className="font-bold text-lg mb-2">Location</h3>
              <p className="text-slate-600">Kottayam, Kerala, India</p>
            </div>
          </div>
        </div>
      </section>

      <footer className="bg-slate-950 text-white text-center py-6 mt-10">
        <p>
          © 2026 MAHIMA SARA JACOB | Electronics & Communication Engineering Portfolio
        </p>
      </footer>
    </div>
  );
}
