# portfolio
portfolio of jahnavi sanjeevan
mport React from 'react';
            <ul className="space-y-4">
              <li className="flex items-start gap-3">
                <Award className="text-blue-600 mt-1" />
                <div>
                  <h3 className="font-semibold">Machine Learning Specialization - Stanford Online</h3>
                  <p className="text-gray-600">Coursera</p>
                </div>
              </li>
              <li className="flex items-start gap-3">
                <Award className="text-blue-600 mt-1" />
                <div>
                  <h3 className="font-semibold">Python for Data Science and Machine Learning</h3>
                  <p className="text-gray-600">IBM</p>
                </div>
              </li>
              <li className="flex items-start gap-3">
                <Award className="text-blue-600 mt-1" />
                <div>
                  <h3 className="font-semibold">Deep Learning Fundamentals</h3>
                  <p className="text-gray-600">DeepLearning.AI</p>
                </div>
              </li>
            </ul>
          </div>
        </section>

        {/* Achievements */}
        <section className="mb-12">
          <h2 className="text-2xl font-bold text-gray-900 mb-4">Achievements</h2>
          <div className="bg-white rounded-lg shadow p-6">
            <ul className="space-y-4">
              <li className="flex items-start gap-3">
                <Award className="text-blue-600 mt-1" />
                <div>
                  <h3 className="font-semibold"> University Hackathon 2023</h3>
                  <p className="text-gray-700">Led a team of 4 to develop an AI-based solution for sustainable agriculture</p>
                </div>
              </li>
              <li className="flex items-start gap-3">
                <Award className="text-blue-600 mt-1" />
                <div>
                  <h3 className="font-semibold">Achieved a good rank in jee mains 79.85</h3>
                  <p className="text-gray-700">computer based Engineering exam conducted by National Testing Agency(NTA)</p>
                </div>
              </li>
            </ul>
          </div>
        </section>
      </main>

      {/* Footer */}
      <footer className="bg-white border-t">
        <div className="max-w-5xl mx-auto px-4 py-6 sm:px-6 lg:px-8">
          <p className="text-center text-gray-600">© 2024 Vaduguru Jahnavi Sanjeevan. All rights reserved.</p>
        </div>
      </footer>
    </div>
  );
}

export default App;

