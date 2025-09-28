import React from 'react'
import { motion } from 'framer-motion'

export default function App() {
  return (
    <div className="bg-gray-50 text-gray-900 font-sans">
      <header className="p-8 text-center bg-gradient-to-r from-green-400 to-blue-500 text-white">
        <h1 className="text-4xl font-bold mb-2">Vishal Kumar Maurya</h1>
        <p className="text-lg">B.Sc (Hons) Agriculture | Aspiring Agri-Tech Innovator</p>
      </header>

      <section className="p-8 max-w-4xl mx-auto">
        <motion.h2 initial={{ opacity: 0 }} animate={{ opacity: 1 }} className="text-2xl font-semibold mb-4">About Me</motion.h2>
        <p className="text-gray-600">
          As an aspiring Agricultural Scholar at Bundelkhand University (2022-2026), my academic journey is enriched with hands-on experience from a recent internship at the Indian Chamber of Food and Agriculture. I am passionate about leveraging technology to improve farming practices and rural livelihoods.
        </p>
        <p className="mt-4 text-gray-600">
          Serving as a Campus Ambassador for Pregrad honed my competencies in sales and communication, equipping me with the ability to advocate effectively for educational opportunities and agricultural innovation.
        </p>
      </section>

      <section className="p-8 max-w-4xl mx-auto">
        <motion.h2 initial={{ opacity: 0 }} animate={{ opacity: 1 }} className="text-2xl font-semibold mb-4">Education</motion.h2>
        <div className="space-y-6">
          <div>
            <h3 className="text-xl font-bold">Bundelkhand University</h3>
            <p>B.Sc Honours in Agriculture A (2022 - 2026)</p>
            <p className="text-gray-600">
              I learned sustainable agriculture practices and modern farming techniques. Actively involved in a 240-hour camp under NSS, contributing to community development and social welfare.
            </p>
          </div>
          <div>
            <h3 className="text-xl font-bold">Uttar Pradesh State Board of High School and Intermediate Education (UPMSP)</h3>
            <p>1290-Ramsurat Malati Intermediate College, Rajgarh Mirzapur</p>
            <p>12th Agriculture | 74.7% (2020 - 2022)</p>
            <p className="text-gray-600">
              I shifted to Ramsurat Malati Intermediate College Mirzapur in Class 11th and 12th to study agriculture.
            </p>
          </div>
          <div>
            <h3 className="text-xl font-bold">Uttar Pradesh State Board of High School and Intermediate Education (UPMSP)</h3>
            <p>1082-Jansewa Intermediate College, Phulwari Sonbhadra</p>
            <p>10th PCMB-CS | 77% (2018 - 2020)</p>
            <p className="text-gray-600">
              I shifted to Jansewa Intermediate College Sonbhadra in Class 8th for a better study environment and because I was interested in computer science.
            </p>
          </div>
        </div>
      </section>

      <section className="p-8 max-w-4xl mx-auto">
        <motion.h2 initial={{ opacity: 0 }} animate={{ opacity: 1 }} className="text-2xl font-semibold mb-4">Licenses & Certifications</motion.h2>
        <ul className="list-disc list-inside space-y-2">
          <li>Career Advancement Bootcamp – Medha (Credential ID: STU243238)</li>
          <li>Agribusiness Knowledge Series – ISAB Greater Noida</li>
          <li>Agriculture 4.0 – The Future of Farming Technology – Just Agriculture (Credential ID: AEEFWS/3757)</li>
          <li>Course on Computer Concepts (CCC) – NIELIT (Credential ID: GO2108034430)</li>
          <li>Fundamentals of Digital Marketing – Google Garage (Credential ID: ZCD 36G ZEF)</li>
        </ul>
      </section>

      <section className="p-8 max-w-4xl mx-auto">
        <motion.h2 initial={{ opacity: 0 }} animate={{ opacity: 1 }} className="text-2xl font-semibold mb-4">Internship</motion.h2>
        <div>
          <h3 className="text-xl font-bold">Indian Chamber of Food and Agriculture</h3>
          <p>Summer Internship (Mar 2024 - May 2024) | New Delhi, Delhi, India</p>
          <p className="text-gray-600">
            Worked on a training report titled “Agriculture Subsidies under Government Schemes.” This remote internship helped me understand various government support programs in agriculture.
          </p>
        </div>
      </section>

      <section className="p-8 max-w-4xl mx-auto">
        <motion.h2 initial={{ opacity: 0 }} animate={{ opacity: 1 }} className="text-2xl font-semibold mb-4">Volunteer Experience</motion.h2>
        <div>
          <h3 className="text-xl font-bold">National Service Scheme (NSS)</h3>
          <p>Volunteer (Aug 2022 - Aug 2024)</p>
          <p className="text-gray-600">
            Volunteered for a 240-hour camp as part of the National Service Scheme (NSS), contributing to community development and social welfare initiatives.
          </p>
        </div>
      </section>

      <footer className="p-6 text-center bg-gray-200">
        <p>© 2025 Vishal Kumar Maurya | All Rights Reserved</p>
      </footer>
    </div>
  )
}
