# Coinflipgamen
1. Identify one problem you encountered in this unit (i.e., during the independent project, not before) and describe how you overcame it. This might be fixing a bug, implementing a feature, or understanding a new concept or skill. Include a code snippet along with your explanation.
   One challenge that I came across is trying to figure out the js part of the code. Since it is a new language it was very hard to understand and impliment in the code.
   
2. How has your understanding of computing changed since the beginning of the semester? Identify at least one specific piece of knowledge, concept, or attitude.
   Since the begining my view on computing was shifted from lines and lines of code to systmes of code variables etc.
   
3. What new skills have you acquired this semester? Identify at least one thing you can do now that you could not do before taking the class.
   Something that I couldnt do was to do 3 different coding languages and defintley not problem solve to make the goal of the code achieved. I couldnt code think like an engineer etc.
   
5. In what ways do computers improve our lives? Explain.
They help us connect with people abroad and automate systems and makes all of ur lives easier.
7. In what ways would our lives be improved by removing computers from our lives? Explain
   Removing computers from our lives could encourage more face-to-face interaction, fostering deeper human connections. It might also promote mindfulness and reduce distractions, allowing for more focused and meaningful experiences. Additionally, it could mitigate privacy concerns and the risks associated with cyber threats.
9. Will being in this class have an impact on you in the future? In what way?
Yes this class is a big major factor of my major i will study data science which requires buisness.



   flipBtn.addEventListener("click", () => {
   let i = Math.floor(Math.random() * 2);
   coin.style.animation = "none";
   if(i){
       setTimeout(function(){
           coin.style.animation = "spin-heads 3s forwards";
       }, 100);
       heads++;
   }
   else{
       setTimeout(function(){
           coin.style.animation = "spin-tails 3s forwards";
       }, 100);
       tails++;
   }

