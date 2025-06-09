<h1 align="center">
  <img src="https://readme-typing-svg.herokuapp.com/?font=Righteous&size=35&center=true&vCenter=true&width=500&height=70&duration=4000&lines=Hello+There...;I'm+Pamudu+Mihranga;Full+Stack+Developer;&color=FFFFFF&background=FFFFFF00&pause=1000" alt="Typing Animation" /><br>
</h1>

```
import React from "react";
import { motion } from "framer-motion";

const AboutMe = () => {
  const name = "Pamudu Mihiranga";
  const role = "Software Engineer";
  const tagline = "Turning coffee into code since 2022";

  const techStack = {
    "IDE": ["IntelliJ IDEA", "VS Code", "WebStorm", "Rider"],
    "App Development": ["Java", "Python", "C#"],
    "Frontend": ["HTML", "CSS", "JavaScript", "React", "Bootstrap", "Tailwind", "jQuery", "Axios"],
    "Backend": ["Hibernate", "MySQL", "Spring", ".NET"],
    "Tools": ["GitHub", "Git", "Firebase", "AWS", "Postman", "Stack Overflow"]
  };

  const socialLinks = [
    { name: "GitHub", url: "https://github.com/yourusername"},
    { name: "LinkedIn", url: "https://linkedin.com/in/yourusername"},
    { name: "Portfolio", url: "https://yourportfolio.com"},
    { name: "Twitter", url: "https://twitter.com/yourusername"}
  ];

  // Animation variants
  const containerVariants = {
    hidden: { opacity: 0 },
    visible: {
      opacity: 1,
      transition: {
        staggerChildren: 0.2,
        delayChildren: 0.3,
      }
    }
  };

  const itemVariants = {
    hidden: { y: 20, opacity: 0 },
    visible: {
      y: 0,
      opacity: 1,
      transition: { type: "spring", stiffness: 100 }
    }
  };

  return (
    <motion.div
      initial="hidden"
      animate="visible"
      variants={containerVariants}
      className="max-w-4xl mx-auto p-8 bg-gradient-to-br from-blue-50 to-purple-50 rounded-3xl shadow-2xl mt-10 border border-opacity-10 border-white overflow-hidden relative"
    >
      {/* Decorative elements */}
      <div className="absolute -top-10 -right-10 w-32 h-32 bg-blue-200 rounded-full opacity-20 blur-xl"></div>
      <div className="absolute -bottom-5 -left-5 w-40 h-40 bg-purple-200 rounded-full opacity-20 blur-xl"></div>

      <motion.div variants={itemVariants}>
        <h1 className="text-4xl font-bold text-transparent bg-clip-text bg-gradient-to-r from-blue-600 to-purple-600">
           Hello, I'm {name}
        </h1>
        <h2 className="text-2xl text-gray-700 mt-2 font-medium">{role}</h2>
        <p className="text-gray-500 italic mt-1">{tagline}</p>
      </motion.div>

      <div className="mt-8">
        <motion.h3 variants={itemVariants} className="text-2xl font-bold text-gray-800 mb-4 flex items-center">
          <span className="mr-2"></span> My Toolbox
        </motion.h3>

        <motion.ul variants={containerVariants} className="grid grid-cols-1 md:grid-cols-2 gap-4">
          {Object.entries(techStack).map(([category, tools]) => (
            <motion.li
              key={category}
              variants={itemVariants}
              whileHover={{ scale: 1.03 }}
              className="p-4 bg-white rounded-xl shadow-md hover:shadow-lg transition-all"
            >
              <span className="font-bold text-lg">{category}</span>
              <div className="flex flex-wrap gap-2 mt-2">
                {tools.map(tool => (
                  <span key={tool} className="px-3 py-1 bg-blue-100 text-blue-800 rounded-full text-sm">
                    {tool}
                  </span>
                ))}
              </div>
            </motion.li>
          ))}
        </motion.ul>
      </div>
  );
};

export default AboutMe;
```
<div align="center">
  <img src="https://techstack-generator.vercel.app/csharp-icon.svg" alt="icon" width="65" height="50"/>
  <img src="https://techstack-generator.vercel.app/java-icon.svg" alt="icon" width="50" height="50" />
  <img src="https://techstack-generator.vercel.app/python-icon.svg" alt="icon" width="50" height="50" />
  <img src="https://techstack-generator.vercel.app/ts-icon.svg" alt="icon" width="50" height="50" />
  <img src="https://techstack-generator.vercel.app/js-icon.svg" alt="icon"width="50" height="50" />
  <img src="https://techstack-generator.vercel.app/react-icon.svg" alt="icon" width="50" height="50" />
  <img src="https://techstack-generator.vercel.app/mysql-icon.svg" alt="icon" width="50" height="50" />
  <img src="https://techstack-generator.vercel.app/redux-icon.svg" alt="icon" width="50" height="50" />
  <img src="https://techstack-generator.vercel.app/nginx-icon.svg" alt="icon" width="50" height="50"/> 
  <img src="https://techstack-generator.vercel.app/docker-icon.svg" alt="icon" width="50" height="50" />
  <img src="https://techstack-generator.vercel.app/aws-icon.svg" alt="icon" width="50" height="50" />
  <img src="https://techstack-generator.vercel.app/restapi-icon.svg" alt="icon" width="50" height="50" />
  <img src="https://techstack-generator.vercel.app/graphql-icon.svg" alt="icon" width="50" height="50" />
  <img src="https://techstack-generator.vercel.app/django-icon.svg" alt="icon" width="50" height="50" />
  <img src="https://techstack-generator.vercel.app/kubernetes-icon.svg" alt="icon" width="50" height="50" />
</div>

