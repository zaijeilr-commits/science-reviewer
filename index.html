import React, { useState } from 'react';
import { ChevronLeft, ChevronRight, Check, X, BookOpen, Award, Lightbulb, Cloud, Beaker, ClipboardList, RotateCcw, AlertCircle, Table, Info } from 'lucide-react';

const App = () => {
  const [view, setView] = useState('summary'); 
  const [currentQuestion, setCurrentQuestion] = useState(0);
  const [selectedOption, setSelectedOption] = useState(null);
  const [showExplanation, setShowExplanation] = useState(false);
  const [answers, setAnswers] = useState(Array(30).fill(null));
  const [quizFinished, setQuizFinished] = useState(false);

  const summaries = [
    {
      title: "1. Periodic Table & History",
      icon: <Beaker className="text-indigo-500" />,
      points: [
        "Antiquity-Middle Ages: 14 elements (Au, Ag, Cu).",
        "1800-1849: 24 new elements; Dobereiner's Law of Triads.",
        "Triad Weights: Li(7), Na(23), K(39) | Ca(40), Sr(88), Ba(137) | Cl(35), Br(80), I(127).",
        "Telluric Helix: Spiral arrangement by weight (De Chancourtois).",
        "Mendeleev: Father of the table; arranged by weight and left gaps.",
        "Moseley: Modern Periodic Law; arranged by Atomic Number.",
        "Metalloids: B, Si, Ge, As, Sb, Te (sometimes Po, At)."
      ]
    },
    {
      title: "2. Metals vs. Non-metals",
      icon: <Info className="text-amber-500" />,
      points: [
        "Metals: 3 or less valence e-, Good conductors, High melting points, Solid form (mostly), High density, Malleable/Ductile.",
        "Non-metals: 4 or more valence e-, Good insulators, Low melting points, Solid/Liquid/Gas form, Low density, Brittle.",
        "Lewis Dot: Symbol = nucleus + inner e-; Dots = valence e-.",
        "Groups: 1A(Alkali), 2A(Alkaline-earth), 3A(Boron), 4A(Tetrels), 5A(Pnictogens), 6A(Chalcogens), 7A(Halogens), 8A(Noble)."
      ]
    },
    {
      title: "3. Formulas & Typhoons",
      icon: <Cloud className="text-blue-500" />,
      points: [
        "Binary Naming: Metal + Non-metal + '-ide'. Molecular uses Greek prefixes (Di, Tri, Tetra, etc).",
        "LPA (Cyclone): Warm moist air, stormy, counter-clockwise in NH.",
        "HPA (Anticyclone): Fair weather, clear skies.",
        "Instruments: Barometer (Pressure), Hygrometer (Humidity), Anemometer (Wind Speed), Rain Gauge (Precipitation).",
        "PAR: Philippine Area of Responsibility (PAGASA)."
      ]
    }
  ];

  const questions = [
    { q: "What is the weight of Sodium (Na) in the Triad Li(7) and K(39)?", options: ["23", "14", "32", "46"], a: 0, ex: "Average: (7+39)/2 = 23." },
    { q: "Which scientist proposed the 'Telluric Helix' spiral?", options: ["Dobereiner", "De Chancourtois", "Newlands", "Moseley"], a: 1, ex: "Alexander de Chancourtois suggested the spiral helix." },
    { q: "How many elements were known in 'Antiquity to Middle Ages'?", options: ["14", "20", "24", "63"], a: 0, ex: "14 elements, including coinage metals." },
    { q: "Metals generally have how many valence electrons?", options: ["3 or less", "4 or more", "Exactly 8", "0"], a: 0, ex: "Metals have 3 or less; Non-metals have 4 or more." },
    { q: "A property of Non-metals is that they are:", options: ["Malleable", "Ductile", "Brittle", "Good conductors"], a: 2, ex: "Non-metals are brittle and break easily." },
    { q: "Which group is known as the 'Pnictogens'?", options: ["4A", "5A", "6A", "7A"], a: 1, ex: "5A = Pnictogens; 6A = Chalcogens." },
    { q: "Which of these is a recognized Metalloid?", options: ["Iron", "Oxygen", "Germanium", "Sodium"], a: 2, ex: "B, Si, Ge, As, Sb, Te are metalloids." },
    { q: "Moseley arranged the modern table by:", options: ["Atomic Weight", "Atomic Number", "Density", "Mass"], a: 1, ex: "Moseley used Atomic Number (protons)." },
    { q: "What is the name for Ag2O?", options: ["Silver Oxide", "Disilver Oxide", "Silver Dioxide", "Silver(I) Oxide"], a: 0, ex: "Ag2O is Silver Oxide." },
    { q: "What is the name for Cl2O5?", options: ["Chlorine Oxide", "Dichlorine Pentoxide", "Chlorine Pentoxide", "Dichlorine Oxide"], a: 1, ex: "Prefixes: Di(2) and Penta(5)." },
    { q: "What is the name for SrS?", options: ["Strontium Sulfate", "Strontium Sulfide", "Strontium Sulfur", "Sulfur Strontide"], a: 1, ex: "Binary ionic ends in -ide: Strontium Sulfide." },
    { q: "Formula for Nitrogen Trioxide:", options: ["NO", "N3O", "NO3", "N2O3"], a: 2, ex: "Nitrogen + 3 Oxide = NO3." },
    { q: "Formula for Zinc Nitride (Zn+2, N-3):", options: ["ZnN", "Zn2N3", "Zn3N2", "ZnN2"], a: 2, ex: "Criss-cross: Zn3N2." },
    { q: "What is the oxidation state of Group 8A?", options: ["+8", "0", "-1", "+1"], a: 1, ex: "Noble gases are stable (0)." },
    { q: "Most metals are found in what form at room temperature?", options: ["Liquid", "Solid", "Gas", "Plasma"], a: 1, ex: "Metals are usually solid (except Hg)." },
    { q: "Non-metals are good _____ of heat and electricity.", options: ["Conductors", "Insulators", "Transmitters", "Reflectors"], a: 1, ex: "Non-metals are good insulators." },
    { q: "Who is the Father of the Periodic Table who left gaps for elements?", options: ["Moseley", "Mendeleev", "Newlands", "Dalton"], a: 1, ex: "Mendeleev predicted future elements." },
    { q: "The dots in a Lewis structure represent:", options: ["Protons", "Inner electrons", "Valence electrons", "Neutrons"], a: 2, ex: "Dots = outer/valence electrons." },
    { q: "A mercury barometer is used to detect changes in:", options: ["Wind speed", "Humidity", "Air pressure", "Rain"], a: 2, ex: "Barometer = Pressure." },
    { q: "What is the whirling mass of air bringing stormy weather?", options: ["HPA", "LPA", "Anticyclone", "Ridge"], a: 1, ex: "LPA (Cyclone) = Stormy." },
    { q: "Winds rotate how in the Northern Hemisphere for an LPA?", options: ["Clockwise", "Counter-clockwise", "Vertical", "Horizontal"], a: 1, ex: "LPA = Counter-clockwise in NH." },
    { q: "Which instrument measures humidity?", options: ["Anemometer", "Barometer", "Hygrometer", "Rain Gauge"], a: 2, ex: "Hygrometer = Humidity." },
    { q: "Which barometer is portable and used in aviation?", options: ["Mercury", "Aneroid", "Water", "Digital"], a: 1, ex: "Aneroid = Portable/Aviation." },
    { q: "What are the rainy months in the Philippines?", options: ["March-May", "June-November", "January-April", "All year"], a: 1, ex: "June to November." },
    { q: "What does PAR stand for?", options: ["Philippine Area of Responsibility", "Pacific Area Region", "Philippine Atmospheric Region", "Private Area Review"], a: 0, ex: "PAR = Philippine Area of Responsibility." },
    { q: "ITCZ is where winds from which hemispheres meet?", options: ["East and West", "North and South", "Up and Down", "Land and Sea"], a: 1, ex: "N and S winds meet at ITCZ." },
    { q: "Air pressure is the force exerted per unit _____.", options: ["Mass", "Volume", "Area", "Density"], a: 2, ex: "Pressure = Force / Area." },
    { q: "What instrument measures wind speed?", options: ["Anemometer", "Hygrometer", "Barometer", "Thermometer"], a: 0, ex: "Anemometer = Wind speed." },
    { q: "Which group is known as the Chalcogens?", options: ["5A", "6A", "7A", "8A"], a: 1, ex: "6A = Chalcogens." },
    { q: "In the Triad Cl(35) and I(127), what is Br?", options: ["80", "40", "88", "23"], a: 0, ex: "Br = 80 per the PDF." }
  ];

  const handleOptionClick = (idx) => {
    if (showExplanation) return;
    const newAnswers = [...answers];
    newAnswers[currentQuestion] = idx;
    setAnswers(newAnswers);
    setSelectedOption(idx);
    setShowExplanation(true);
  };

  const nextQuestion = () => {
    if (currentQuestion < 29) {
      setCurrentQuestion(currentQuestion + 1);
      setSelectedOption(answers[currentQuestion + 1]);
      setShowExplanation(answers[currentQuestion + 1] !== null);
    } else {
      setQuizFinished(true);
    }
  };

  const prevQuestion = () => {
    if (currentQuestion > 0) {
      setCurrentQuestion(currentQuestion - 1);
      setSelectedOption(answers[currentQuestion - 1]);
      setShowExplanation(true);
    }
  };

  const calculateScore = () => {
    return answers.reduce((acc, curr, idx) => (curr === questions[idx].a ? acc + 1 : acc), 0);
  };

  const finalScore = quizFinished ? calculateScore() : 0;
  const isPassed = finalScore >= 18;

  return (
    <div className="min-h-screen bg-slate-100 text-slate-900 p-4 md:p-8 font-sans">
      <div className="max-w-5xl mx-auto">
        
        {/* Navigation Tabs */}
        <div className="flex bg-white rounded-2xl shadow-md p-1.5 mb-8 border border-slate-200">
          <button onClick={() => setView('summary')} className={`flex-1 py-3 rounded-xl font-bold transition-all ${view === 'summary' ? 'bg-indigo-600 text-white shadow-lg' : 'text-slate-500'}`}>Summary</button>
          <button onClick={() => setView('table')} className={`flex-1 py-3 rounded-xl font-bold transition-all ${view === 'table' ? 'bg-indigo-600 text-white shadow-lg' : 'text-slate-500'}`}>Periodic Data</button>
          <button onClick={() => setView('quiz')} className={`flex-1 py-3 rounded-xl font-bold transition-all ${view === 'quiz' ? 'bg-indigo-600 text-white shadow-lg' : 'text-slate-500'}`}>Final Exam</button>
        </div>

        {view === 'summary' ? (
          <div className="grid md:grid-cols-3 gap-6 animate-in fade-in">
            {summaries.map((item, i) => (
              <div key={i} className="bg-white p-6 rounded-3xl border border-slate-200 shadow-sm">
                <div className="flex items-center gap-3 mb-6">
                  <div className="p-2 bg-indigo-50 rounded-xl text-indigo-600">{item.icon}</div>
                  <h3 className="font-black text-slate-800 tracking-tight">{item.title}</h3>
                </div>
                <ul className="space-y-4">
                  {item.points.map((p, j) => (
                    <li key={j} className="text-[11px] text-slate-600 flex gap-3 leading-relaxed">
                      <span className="text-indigo-400 font-bold">•</span> {p}
                    </li>
                  ))}
                </ul>
              </div>
            ))}
          </div>
        ) : view === 'table' ? (
          <div className="space-y-6 animate-in zoom-in-95">
            <div className="bg-white p-8 rounded-[2.5rem] shadow-xl border border-slate-200">
              <h2 className="text-xl font-black mb-6 flex items-center gap-2">Metals vs. Non-metals (Page 19)</h2>
              <table className="w-full text-xs text-left">
                <thead className="bg-slate-50">
                  <tr>
                    <th className="p-3 border-b">Feature</th>
                    <th className="p-3 border-b text-indigo-600">Metals</th>
                    <th className="p-3 border-b text-amber-600">Non-metals</th>
                  </tr>
                </thead>
                <tbody>
                  <tr><td className="p-3 border-b font-bold">Valence e-</td><td className="p-3 border-b">3 or lesser</td><td className="p-3 border-b">4 or more</td></tr>
                  <tr><td className="p-3 border-b font-bold">Conduction</td><td className="p-3 border-b">Good (Heat/Electricity)</td><td className="p-3 border-b">Good Insulators</td></tr>
                  <tr><td className="p-3 border-b font-bold">Melting Points</td><td className="p-3 border-b">High</td><td className="p-3 border-b">Low</td></tr>
                  <tr><td className="p-3 border-b font-bold">State</td><td className="p-3 border-b">Mostly Solid</td><td className="p-3 border-b">Solid, Liquid, Gas</td></tr>
                  <tr><td className="p-3 border-b font-bold">Mechanical</td><td className="p-3 border-b">Malleable, Ductile</td><td className="p-3 border-b">Brittle</td></tr>
                </tbody>
              </table>
            </div>
            <div className="bg-indigo-900 text-white p-6 rounded-3xl shadow-lg">
              <h3 className="font-bold mb-3">Recognized Metalloids (Diagonal zig-zag)</h3>
              <p className="text-sm text-indigo-200">B, Si, Ge, As, Sb, Te (sometimes Po, At)</p>
            </div>
          </div>
        ) : !quizFinished ? (
          <div className="bg-white rounded-[2.5rem] shadow-2xl border border-slate-100 overflow-hidden animate-in slide-in-from-bottom-6">
            <div className="bg-slate-900 p-6 flex justify-between items-center text-white">
              <span className="text-xs font-black uppercase tracking-[0.2em]">Question {currentQuestion + 1} / 30</span>
              <div className="h-1.5 w-32 bg-slate-800 rounded-full overflow-hidden">
                <div className="h-full bg-indigo-500" style={{ width: `${((currentQuestion + 1)/30)*100}%` }} />
              </div>
            </div>

            <div className="p-10 md:p-16">
              <h3 className="text-2xl font-black text-slate-800 mb-10 leading-snug">{questions[currentQuestion].q}</h3>
              <div className="grid gap-4 mb-10">
                {questions[currentQuestion].options.map((opt, i) => {
                  const isCorrect = i === questions[currentQuestion].a;
                  const isSelected = i === selectedOption;
                  let btnClass = "w-full p-6 rounded-2xl border-2 text-left font-bold transition-all flex justify-between items-center ";
                  if (showExplanation) {
                    if (isCorrect) btnClass += "border-green-500 bg-green-50 text-green-800";
                    else if (isSelected) btnClass += "border-red-500 bg-red-50 text-red-800";
                    else btnClass += "border-slate-100 text-slate-300";
                  } else btnClass += "border-slate-100 hover:border-indigo-400 hover:bg-indigo-50";

                  return (
                    <button key={i} disabled={showExplanation} onClick={() => handleOptionClick(i)} className={btnClass}>
                      <span>{opt}</span>
                      {showExplanation && isCorrect && <Check className="text-green-600" />}
                      {showExplanation && isSelected && !isCorrect && <X className="text-red-600" />}
                    </button>
                  );
                })}
              </div>

              {showExplanation && (
                <div className="bg-slate-900 text-slate-100 p-6 rounded-3xl mb-10 flex gap-4">
                  <Lightbulb className="text-yellow-400 shrink-0" />
                  <p className="text-sm"><b>Official Review:</b> {questions[currentQuestion].ex}</p>
                </div>
              )}

              <div className="flex justify-between items-center pt-8 border-t">
                <button onClick={prevQuestion} className={`font-black text-slate-400 ${currentQuestion === 0 ? 'invisible' : ''}`}>Back</button>
                <button onClick={nextQuestion} disabled={selectedOption === null} className="bg-indigo-600 text-white px-10 py-4 rounded-2xl font-black shadow-lg">
                  {currentQuestion === 29 ? 'Finish' : 'Next'}
                </button>
              </div>
            </div>
          </div>
        ) : (
          <div className="bg-white rounded-[3.5rem] shadow-2xl p-16 text-center border border-slate-100">
            <h2 className={`text-6xl font-black mb-4 ${isPassed ? 'text-green-600' : 'text-red-600'}`}>{isPassed ? 'PASSED' : 'FAILED'}</h2>
            <p className="text-slate-400 mb-12 text-xl font-bold">Final Score: {finalScore}/30</p>
            <button onClick={() => window.location.reload()} className="bg-slate-900 text-white px-12 py-6 rounded-[2rem] font-black">Restart Review</button>
          </div>
        )}
      </div>
    </div>
  );
};

export default App;
