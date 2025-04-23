import { Card, CardContent } from "@/components/ui/card";
import { Button } from "@/components/ui/button";

export default function Portfolio() {
  return (
    <div className="bg-gray-100 min-h-screen px-6 py-12">
      <div className="max-w-5xl mx-auto">
        <header className="text-center mb-12">
          <h1 className="text-5xl font-bold text-gray-800">Dinesh Singh</h1>
          <p className="mt-2 text-lg text-gray-600">Aspiring Machine Learning Engineer</p>
          <div className="mt-4 flex flex-wrap justify-center gap-4 text-sm text-gray-700">
            <a href="https://www.linkedin.com/in/dinesh-singh1/" target="_blank" className="hover:underline">LinkedIn</a>
            <a href="https://github.com/77Dinesh" target="_blank" className="hover:underline">GitHub</a>
            <span>Email: dineshsinghk36@gmail.com</span>
            <span>Phone: +91-9306920218</span>
          </div>
        </header>

        <section className="mb-12">
          <h2 className="text-3xl font-semibold mb-6 text-center">Skills</h2>
          <Card>
            <CardContent className="p-6 grid grid-cols-1 md:grid-cols-2 gap-4">
              <div><strong>Languages:</strong> C++, Python, C, Java</div>
              <div><strong>Frameworks:</strong> Pandas, Scikit-Learn, Matplotlib, Seaborn</div>
              <div><strong>Tools/Platforms:</strong> MySQL</div>
              <div><strong>Soft Skills:</strong> Problem-Solving, Team Player, Project Management, Adaptability</div>
            </CardContent>
          </Card>
        </section>

        <section className="mb-12">
          <h2 className="text-3xl font-semibold mb-6 text-center">Projects</h2>
          <div className="space-y-6">
            <Card>
              <CardContent className="p-6">
                <h3 className="text-xl font-bold">Breast Cancer Prediction</h3>
                <p>Developed a predictive model using Decision Tree and Random Forest on the Wisconsin Breast Cancer Database to classify tumors.</p>
                <p className="mt-2"><strong>Tech:</strong> Python, Pandas, Scikit-Learn, Matplotlib, Seaborn</p>
              </CardContent>
            </Card>
            <Card>
              <CardContent className="p-6">
                <h3 className="text-xl font-bold">Helping Hands – Complaint Registration</h3>
                <p>A web platform where users can register complaints regarding social issues like poor infrastructure.</p>
                <p className="mt-2"><strong>Tech:</strong> HTML, JavaScript, CSS</p>
              </CardContent>
            </Card>
          </div>
        </section>

        <section className="mb-12">
          <h2 className="text-3xl font-semibold mb-6 text-center">Certifications</h2>
          <ul className="list-disc list-inside text-gray-800 px-4">
            <li>Getting Started with AI and Machine Learning – Sep 2024</li>
            <li>Prompt Engineering for ChatGPT – Feb 2024</li>
            <li>Dynamic Programming and Greedy Algorithms – Apr 2024</li>
            <li>Algorithms of Strings – Feb 2024</li>
          </ul>
        </section>

        <section className="mb-12">
          <h2 className="text-3xl font-semibold mb-6 text-center">Co-Curricular Activities</h2>
          <ul className="list-disc list-inside text-gray-800 px-4">
            <li>Interview Preparation Workshop – Dec 2024</li>
            <li>Hackathon Participation – Sep 2024</li>
            <li>Public Speaking Workshop – Jan 2023</li>
            <li>Analytical Skills Workshop – Sep 2024</li>
          </ul>
        </section>

        <section className="mb-12">
          <h2 className="text-3xl font-semibold mb-6 text-center">Education</h2>
          <ul className="list-disc list-inside text-gray-800 px-4">
            <li>B.Tech in Computer Science & Engineering – Lovely Professional University, CGPA: 6.18 (Since Aug 2022)</li>
            <li>Intermediate – Yaduvanshi Shiksha Niketan, 80% (2021-2022)</li>
            <li>Matriculation – Yaduvanshi Shiksha Niketan, 84% (2019-2020)</li>
          </ul>
        </section>

        <footer className="text-center text-sm text-gray-500 mt-12">
          &copy; {new Date().getFullYear()} Dinesh Singh. All rights reserved.
        </footer>
      </div>
    </div>
  );
}
