export default function Dashboard() {
  const stats = [
    { title: "Website Traffic", value: "124K" },
    { title: "Conversion Rate", value: "4.2%" },
    { title: "Revenue Generated", value: "₹3.8L" },
    { title: "AI SEO Score", value: "92%" },
  ];

  return (
    <main className="min-h-screen bg-gray-100 p-8">
      <h1 className="text-3xl font-bold mb-6">
        AI-Driven Marketing Dashboard
      </h1>

      <div className="grid grid-cols-1 md:grid-cols-4 gap-6">
        {stats.map((item, index) => (
          <div
            key={index}
            className="bg-white p-6 rounded-xl shadow-md"
          >
            <h2 className="text-gray-500">{item.title}</h2>
            <p className="text-2xl font-bold mt-2">{item.value}</p>
          </div>
        ))}
      </div>
    </main>
  );
}
