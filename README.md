import React from "react";

const Dashboard = () => {
  return (
    <div className="flex h-screen bg-gray-100">
      {/* Sidebar */}
      <aside className="w-64 bg-white shadow-md">
        <div className="p-4 text-xl font-bold text-center border-b">Dashboard</div>
        <nav className="p-4">
          <ul>
            <li className="mb-2">
              <a
                href="#overview"
                className="block px-4 py-2 text-gray-700 rounded hover:bg-gray-200"
              >
                Overview
              </a>
            </li>
            <li className="mb-2">
              <a
                href="#reports"
                className="block px-4 py-2 text-gray-700 rounded hover:bg-gray-200"
              >
                Reports
              </a>
            </li>
            <li className="mb-2">
              <a
                href="#settings"
                className="block px-4 py-2 text-gray-700 rounded hover:bg-gray-200"
              >
                Settings
              </a>
            </li>
          </ul>
        </nav>
      </aside>


      <div className="flex-1 flex flex-col">

        <header className="h-16 bg-white shadow flex items-center px-6">
          <h1 className="text-xl font-semibold">Welcome to Your Dashboard</h1>
        </header>

     
        <main className="flex-1 p-6 overflow-y-auto">
          <div className="grid grid-cols-1 gap-6 md:grid-cols-2 lg:grid-cols-3">
      
            <div className="p-4 bg-white rounded shadow">
              <h2 className="text-lg font-semibold">Widget 1</h2>
              <p className="mt-2 text-gray-600">Details about widget 1.</p>
            </div>

            <div className="p-4 bg-white rounded shadow">
              <h2 className="text-lg font-semibold">Widget 2</h2>
              <p className="mt-2 text-gray-600">Details about widget 2.</p>
            </div>
             Hey Kay yes i'm thinkin/missing(you) about you i just thought ki
             why not tumhe bta hi diya jae ki i'm so sending this letter to you 
             aur ye pta nhi kyu sunflower nhi milte time pe par 

            <div className="p-4 bg-white rounded shadow">
              <h2 className="text-lg font-semibold">Widget 3</h2>
              <p className="mt-2 text-gray-600">Details about widget 3.</p>
            </div>
          </div>
        </main>
      </div>
    </div>
  );
};

export default Dashboard;
