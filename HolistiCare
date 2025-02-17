<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HolistiCare - Ayurvedic Remedies</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #f4f4f4;
            color: black;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #4caf50;
            color: white;
            padding: 20px;
            text-align: center;
        }
        nav {
            background-color: #388e3c;
            color: white;
            padding: 10px;
            text-align: center;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-size: 18px;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .content {
            padding: 20px;
            margin: 20px;
            background-color: white;
            border-radius: 10px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }
        .form-container {
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        .form-container input, .form-container button {
            padding: 10px;
            margin: 5px;
            font-size: 16px;
            width: 80%;
            max-width: 400px;
            border-radius: 5px;
            border: 1px solid #ccc;
        }
        .form-container button {
            background-color: #388e3c;
            color: white;
            cursor: pointer;
        }
        .form-container button:hover {
            background-color: #4caf50;
        }
        .tabs {
            display: flex;
            justify-content: center;
            margin-top: 20px;
        }
        .tabs div {
            padding: 10px 20px;
            margin: 0 10px;
            cursor: pointer;
            background-color: #388e3c;
            color: white;
            border-radius: 5px;
        }
        .tabs div:hover {
            background-color: #4caf50;
        }
        .tabs-content {
            margin-top: 20px;
        }
        .remedy {
            background-color: #e8f5e9;
            padding: 15px;
            margin: 10px 0;
            border-radius: 5px;
            border: 1px solid #c8e6c9;
        }
        .remedy img {
            width: 80px;
            height: 80px;
            margin-right: 10px;
            vertical-align: middle;
        }
    </style>
</head>
<body>

<header>
    <h1>Welcome to HolistiCare</h1>
    <p>Explore natural, holistic remedies for various diseases based on Ayurvedic principles.</p>
</header>

<nav>
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#lim">Leader in Me (LIM)</a>
</nav>

<div class="content" id="homeContent">
    <h2>Discover the Power of Ayurveda</h2>
    <p>Ayurveda, the ancient science of life, has been practiced for thousands of years to promote health and wellness. This holistic system emphasizes the balance of mind, body, and spirit, and offers remedies that harness the healing power of nature.</p>
    <button onclick="showDetailsForm()">Continue</button>
</div>

<div class="content" id="detailsFormContent" style="display:none;">
    <h2>Enter Your Details</h2>
    <div class="form-container">
        <input type="text" id="name" placeholder="Enter your name" required>
        <input type="number" id="age" placeholder="Enter your age" required oninput="suggestVitals()">
        <input type="number" id="height" placeholder="Enter your height (cm)" required>
        <input type="number" id="weight" placeholder="Enter your weight (kg)" required>
        <input type="number" id="pulseRate" placeholder="Enter your pulse rate (beats per minute)" required>
        <div id="vitalSuggestions"></div>
        <input type="text" id="diseaseInput" placeholder="Enter Disease (e.g., Cold)" required>
        <button onclick="showRemedy()">Get Remedy</button>
    </div>
</div>

<div class="content" id="remedyOutput" style="display:none;">
    <h2>Remedy</h2>
    <div class="remedy" id="remedyText"></div>
</div>

<div class="content hidden" id="about">
    <h2>About HolistiCare</h2>
    <p>At HolistiCare, we embrace the timeless wisdom of Ayurveda to help you achieve balance, healing, and overall well-being. Our mission is to offer you authentic, carefully researched remedies and holistic health solutions to support your journey toward a healthier life. By following key principles from Ayurveda and effective personal development habits, we strive to provide you with valuable resources that promote long-term wellness.</p>
</div>

<div class="content hidden" id="lim">
    <h2>Leader in Me (LIM)</h2>
    <p>The Leader in Me program is a philosophy and educational framework based on timeless principles of leadership, focused on empowering individuals to achieve their full potential. HolistiCare implements LIM principles to inspire positive change and personal growth within our community.</p>
    <p>LIM emphasizes the importance of self-leadership, responsibility, and accountability, all of which are crucial for personal and professional development. At HolistiCare, we incorporate LIM into our Ayurvedic practices to help individuals lead healthy and fulfilling lives.</p>
    <p>By adopting LIM principles, we aim to nurture leadership qualities in our clients, teaching them to take charge of their health, set meaningful goals, and work towards creating positive impacts in their lives and communities.</p>
    <p>We focus on empowering individuals to make informed decisions regarding their health, encouraging them to lead by example and inspire others to follow their path to wellness. The LIM framework allows us to focus on individual growth and well-being within the holistic health context.</p>
    <p>HolistiCare believes that by integrating Ayurvedic practices with leadership principles, we can foster a more balanced, empowered, and resilient community. Our commitment to LIM is reflected in our personalized guidance, resources, and support systems that drive success and wellness.</p>
    <p>Through LIM, we encourage individuals to adopt a mindset of continuous improvement, strengthening both their body and mind. It’s a comprehensive approach that helps each individual thrive in all areas of their life.</p>

    <h3>Key Habits in Leader in Me (LIM):</h3>
    <ul>
        <li><strong>Habit 1: Be Proactive</strong> – Take control of your health journey by making informed decisions about your Ayurvedic remedies and wellness practices.</li>
        <li><strong>Habit 2: Begin with the End in Mind</strong> – Set clear health goals and envision your future well-being with Ayurveda guiding your path.</li>
        <li><strong>Habit 3: Put First Things First</strong> – Prioritize essential Ayurvedic practices that enhance your health, such as daily routines and diet adjustments.</li>
        <li><strong>Habit 4: Think Win-Win</strong> – Seek mutual benefits by sharing effective Ayurvedic solutions with others and promoting collective wellness.</li>
        <li><strong>Habit 5: Seek First to Understand, Then to Be Understood</strong> – Listen to your body and seek personalized Ayurvedic advice based on your unique health needs.</li>
        <li><strong>Habit 7: Sharpen the Saw</strong> – Continuously improve your health by maintaining balance and rejuvenating your body and mind with regular Ayurvedic practices.</li>
    </ul>
</div>

<script>
    const diseaseRemedies = {
        "Cold": {
            remedy: "Drink warm herbal teas like ginger tea and use steam inhalation with eucalyptus oil.",
            image: "https://via.placeholder.com/80/ff6347?text=Cold"
        },
        "Thyroid": {
            remedy: "Consume ashwagandha, flaxseeds, and increase iodine intake through natural sources like seaweed.",
            image: "https://via.placeholder.com/80/ff6347?text=Thyroid"
        },
        "Blood Pressure": {
            remedy: "Drink hibiscus tea, reduce salt intake, and practice deep breathing exercises.",
            image: "https://via.placeholder.com/80/ff6347?text=Blood+Pressure"
        },
        "Diabetes": {
            remedy: "Consume bitter melon, fenugreek, and increase fiber intake. Regular exercise is essential.",
            image: "https://via.placeholder.com/80/ff6347?text=Diabetes"
        },
        "Asthma": {
            remedy: "Take turmeric with honey, avoid cold air, and use a warm salt water gargle.",
            image: "https://via.placeholder.com/80/ff6347?text=Asthma"
        },
        "Insomnia": {
            remedy: "Drink chamomile tea and practice meditation or yoga before bed.",
            image: "https://via.placeholder.com/80/ff6347?text=Insomnia"
        },
        "Acne": {
            remedy: "Apply aloe vera gel, turmeric paste, and avoid oily foods.",
            image: "https://via.placeholder.com/80/ff6347?text=Acne"
        },
        "Arthritis": {
            remedy: "Consume turmeric, ginger, and practice gentle yoga to improve joint flexibility.",
            image: "https://via.placeholder.com/80/ff6347?text=Arthritis"
        },
        "Migraine": {
            remedy: "Massage with peppermint oil and apply a cold compress to the forehead.",
            image: "https://via.placeholder.com/80/ff6347?text=Migraine"
        },
        "Fatigue": {
            remedy: "Drink ginger tea, consume foods rich in iron, and get adequate rest.",
            image: "https://via.placeholder.com/80/ff6347?text=Fatigue"
        },
        "Indigestion": {
            remedy: "Consume ginger or fennel tea and avoid heavy meals late at night.",
            image: "https://via.placeholder.com/80/ff6347?text=Indigestion"
        },
        "Cough": {
            remedy: "Drink warm honey-lemon water, and use steam inhalation with eucalyptus oil.",
            image: "https://via.placeholder.com/80/ff6347?text=Cough"
        },
        "Eczema": {
            remedy: "Apply coconut oil and aloe vera, and avoid skin irritants.",
            image: "https://via.placeholder.com/80/ff6347?text=Eczema"
        },
        "Sore Throat": {
            remedy: "Gargle with warm salt water and drink warm herbal teas.",
            image: "https://via.placeholder.com/80/ff6347?text=Sore+Throat"
        },
        "Headaches": {
            remedy: "Massage your temples with peppermint oil and hydrate well.",
            image: "https://via.placeholder.com/80/ff6347?text=Headaches"
        },
        "Obesity": {
            remedy: "Increase fiber intake, exercise regularly, and drink detox teas.",
            image: "https://via.placeholder.com/80/ff6347?text=Obesity"
        },
        "Urinary Tract Infection (UTI)": {
            remedy: "Drink plenty of water, consume cranberry juice, and use warm compresses.",
            image: "https://via.placeholder.com/80/ff6347?text=UTI"
        },
        "Depression": {
            remedy: "Take Brahmi, Ashwagandha, and engage in regular physical activity.",
            image: "https://via.placeholder.com/80/ff6347?text=Depression"
        },
        "Stress": {
            remedy: "Practice meditation, yoga, and drink calming herbal teas like chamomile.",
            image: "https://via.placeholder.com/80/ff6347?text=Stress"
        },
        "High Cholesterol": {
            remedy: "Consume garlic, ginger, and increase fiber intake with oats and flaxseeds.",
            image: "https://via.placeholder.com/80/ff6347?text=Cholesterol"
        },
        "Acidity": {
            remedy: "Drink cold milk or coconut water and avoid spicy foods.",
            image: "https://via.placeholder.com/80/ff6347?text=Acidity"
        },
        "Anemia": {
            remedy: "Consume iron-rich foods like spinach, dates, and increase vitamin C intake.",
            image: "https://via.placeholder.com/80/ff6347?text=Anemia"
        },
        "Sinusitis": {
            remedy: "Use steam inhalation, drink ginger tea, and apply warm compresses.",
            image: "https://via.placeholder.com/80/ff6347?text=Sinusitis"
        },
        "Osteoporosis": {
            remedy: "Increase calcium intake with dairy and leafy greens, and do weight-bearing exercises.",
            image: "https://via.placeholder.com/80/ff6347?text=Osteoporosis"
        },
        "Menstrual Cramps": {
            remedy: "Consume ginger tea and apply heat pads to the abdomen.",
            image: "https://via.placeholder.com/80/ff6347?text=Menstrual+Cramps"
        },
        "Celiac Disease": {
            remedy: "Avoid gluten-containing foods and increase fiber and vitamin-rich foods.",
            image: "https://via.placeholder.com/80/ff6347?text=Celiac+Disease"
        },
        "PMS (Premenstrual Syndrome)": {
            remedy: "Drink fennel tea and consume magnesium-rich foods like nuts and leafy greens.",
            image: "https://via.placeholder.com/80/ff6347?text=PMS"
        },
        "Bloating": {
            remedy: "Drink peppermint or ginger tea and avoid carbonated drinks.",
            image: "https://via.placeholder.com/80/ff6347?text=Bloating"
        },
        "Gastritis": {
            remedy: "Avoid spicy foods, drink aloe vera juice, and consume soft, bland foods.",
            image: "https://via.placeholder.com/80/ff6347?text=Gastritis"
        },
        "Kidney Stones": {
            remedy: "Increase water intake, drink lemon juice, and consume pomegranate juice.",
            image: "https://via.placeholder.com/80/ff6347?text=Kidney+Stones"
        },
        "Jaundice": {
            remedy: "Consume amla (Indian gooseberry) juice, and drink plenty of water.",
            image: "https://via.placeholder.com/80/ff6347?text=Jaundice"
        }
    };

    function suggestVitals() {
        const age = parseInt(document.getElementById('age').value);
        const pulseRate = document.getElementById('pulseRate');
        const height = document.getElementById('height');
        const weight = document.getElementById('weight');
        const vitalSuggestions = document.getElementById('vitalSuggestions');
        
        if (age) {
            // Pulse Rate suggestions
            let pulseSuggestion = '';
            if (age <= 1) {
                pulseSuggestion = 'Suggested Pulse Rate: 120-160 bpm (Newborn)';
            } else if (age <= 10) {
                pulseSuggestion = 'Suggested Pulse Rate: 70-130 bpm (Child)';
            } else if (age <= 17) {
                pulseSuggestion = 'Suggested Pulse Rate: 60-100 bpm (Adolescent)';
            } else if (age <= 60) {
                pulseSuggestion = 'Suggested Pulse Rate: 60-100 bpm (Adult)';
            } else {
                pulseSuggestion = 'Suggested Pulse Rate: 60-90 bpm (Older Adult)';
            }

            // Height suggestions
            let heightSuggestion = '';
            if (age <= 1) {
                heightSuggestion = 'Suggested Height: 50-75 cm';
            } else if (age <= 5) {
                heightSuggestion = 'Suggested Height: 80-110 cm';
            } else if (age <= 12) {
                heightSuggestion = 'Suggested Height: 120-150 cm';
            } else if (age <= 18) {
                heightSuggestion = 'Suggested Height: 150-170 cm (varies by gender)';
            } else {
                heightSuggestion = 'Suggested Height: 160-180 cm (varies by gender)';
            }

            // Weight suggestions
            let weightSuggestion = '';
            if (age <= 1) {
                weightSuggestion = 'Suggested Weight: 3.5-10 kg';
            } else if (age <= 5) {
                weightSuggestion = 'Suggested Weight: 10-20 kg';
            } else if (age <= 12) {
                weightSuggestion = 'Suggested Weight: 20-50 kg';
            } else if (age <= 18) {
                weightSuggestion = 'Suggested Weight: 40-70 kg';
            } else {
                weightSuggestion = 'Suggested Weight: 50-90 kg (varies by body type)';
            }

            vitalSuggestions.innerHTML = `
                <p>${pulseSuggestion}</p>
                <p>${heightSuggestion}</p>
                <p>${weightSuggestion}</p>
            `;
        }
    }

    function showDetailsForm() {
        document.getElementById('homeContent').style.display = 'none';
        document.getElementById('detailsFormContent').style.display = 'block';
    }

    function showRemedy() {
        const disease = document.getElementById("diseaseInput").value.trim();
        const remedy = diseaseRemedies[disease];

        if (remedy) {
            document.getElementById("remedyText").innerHTML = `
                <img src="${remedy.image}" alt="${disease} Remedy">
                <strong>Remedy for ${disease}:</strong>
                <p>${remedy.remedy}</p>
            `;
        } else {
            document.getElementById("remedyText").innerHTML = `
                <strong>We're Sorry!</strong> We don't have a remedy for "${disease}" yet. Please consult an Ayurvedic expert for guidance.
            `;
        }
        document.getElementById('detailsFormContent').style.display = 'none';
        document.getElementById('remedyOutput').style.display = 'block';
    }
</script>

</body>
</html>
