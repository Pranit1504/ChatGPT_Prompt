### Problem : Write a ChatGPT Prompt which takes your Resume as input and parse the content in JSON format.

## Solution : The ChatGPT prompt can be written as :

I need your help to turn my resume into a JSON format. I'll paste my resume below, and I'd like you to extract the information and organize it into JSON. Here’s what I need in the JSON:

- Personal Information (Name, Email, Phone, Address)
- Summary (Objective)
- Education (Degree, University, Year)
- Experience (Job Title, Company, Dates, Responsibilities)
- Skills (Technical Skills, Soft Skills)
- Projects (Title, Description, Technologies Used)
- Certifications (Name, Issuer, Date)

Here's my resume:

// Enter Resume text //

Parse this and give me the JSON output.


Note :  I have used my own resume to test the prompt.

### ChatGPT output for the given prompt to parse the resume in JSON format :
<pre>
{
  "personal_information": {
    "name": "Pranit Lonkar",
    "email": "pranitlonkar15@gmail.com",
    "phone": "+91 8830765761",
    "address": "Pune, India",
    "linkedin": "www.linkedin.com/in/pranit-lonkar",
    "github": "https://github.com/Pranit1504"
  },
  "summary": null,
  "education": [
    {
      "degree": "10th Class (SSC)",
      "university": "VP's Magarpatta City Public School, Pune",
      "year": "March 2019",
      "percentage": "97.2%"
    },
    {
      "degree": "12th Class (HSC)",
      "university": "The Orbis School, Keshavnagar, Pune",
      "year": "July 2021",
      "percentage": "90%"
    },
    {
      "degree": "B.Tech",
      "university": "B.R.A.C.T's Vishwakarma Institute of Information Technology, Kondhwa",
      "year": "Expected July 2025",
      "department": "Artificial Intelligence and Data Science (3rd Yr)",
      "cgpa": "9.2"
    }
  ],
  "experience": [],
  "skills": {
    "technical_skills": [
      "HTML",
      "CSS",
      "Bootstrap",
      "JavaScript",
      "jQuery",
      "React",
      "Next.js",
      "Node.js",
      "Express.js",
      "EJS",
      "MySQL",
      "MongoDB",
      "Mongoose",
      "Python",
      "Java"
    ],
    "soft_skills": []
  },
  "projects": [
    {
      "title": "Blog Website - CuriousCafe",
      "description": "Developed a robust full-stack blogging platform utilizing Next.js for the frontend and MongoDB for backend storage. Implemented secure user authentication and CRUD operations for blog management, ensuring data integrity and user privacy. Designed and integrated intuitive category exploration and search functionalities, enhancing user experience and engagement. Demonstrated proficiency in Next.js architecture and best practices, resulting in a scalable and efficient application design.",
      "technologies_used": [
        "HTML",
        "CSS",
        "JavaScript",
        "Next.js"
      ],
      "date": "August 2023"
    },
    {
      "title": "Voice Screen Lock",
      "description": "Developed a screen lock system utilizing speech recognition technology for user authentication by implemented audio analysis modules to validate device ownership based on voice input, enhancing device security.",
      "technologies_used": [
        "Python",
        "Speech Recognition"
      ],
      "date": "May 2022"
    },
    {
      "title": "Library Management System",
      "description": "Developed and implemented a library management system, optimizing core housekeeping functions and enhancing member services. Utilized file handling techniques for data storage and management.",
      "technologies_used": [
        "C++",
        "File Handling"
      ],
      "date": "May 2023"
    },
    {
      "title": "Story Generator using Generative AI",
      "description": "Contributed in the development of a sophisticated story generator leveraging Generative AI technology. Utilized the TinyLLama Language Model (LLM) as the foundation and fine-tuned it with a proprietary dataset of prompts and stories. This process involved training the model to dynamically generate stories based on user inputs.",
      "technologies_used": [
        "Python",
        "LLM",
        "AI/ML"
      ],
      "date": "February 2024"
    },
    {
      "title": "Alzheimer’s Detection using Deep Learning",
      "description": "Contributed in a deep learning project aimed at early-stage Alzheimer's detection using Convolutional Neural Networks (CNN). The project involves developing and training a CNN model to classify MRI images into relevant categories using TensorFlow or PyTorch frameworks. Designing and implementing a web application interface to facilitate user input of MRI images and display prediction results. Under the guidance of Prof. Swapnil Shinde, VIIT Pune MH.",
      "technologies_used": [
        "Python",
        "Deep Learning",
        "Web Dev",
        "TensorFlow",
        "PyTorch"
      ],
      "date": "Current"
    }
  ],
  "certifications": [
    {
      "name": "Supervised Machine Learning: Regression and Classification",
      "issuer": "Andrew Ng, Udemy",
      "date": null
    },
    {
      "name": "Python Data Structures and Algorithms + LEETCODE Exercises",
      "issuer": "Scott Barrett, Udemy",
      "date": null
    },
    {
      "name": "The Complete Web Development Bootcamp",
      "issuer": "Angela Yu, Udemy",
      "date": null
    },
    {
      "name": "Backend Web Development Bootcamp using Node.js and Express",
      "issuer": "Shaurya Sinha, DevtTown",
      "date": null
    },
    {
      "name": "Data Analytics with Specialization in Tableau Workshop",
      "issuer": "Shiva Vashishtha, Jobaaj",
      "date": null
    }
  ]
}
</pre>


