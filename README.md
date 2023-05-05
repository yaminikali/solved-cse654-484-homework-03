Download Link: https://assignmentchef.com/product/solved-cse654-484-homework-03
<br>
In this homework, we will use the Turkish language model that we developed for HW2 to correct Turkish sentences written using English letters only. For example, if the input sentence is “beklenen olumlu tepkiyi alamadi”, the output sentence will be “beklenen olumlu tepkiyi alamadı”. Note that “olumlu” could have been “ölümlü” but we did not choose it.




Your task is to use your language model to assign probability values for each possible sentence and make your decision based on the result. Here are the steps that you may use to complete this task

<ul>

 <li>Input the sentence written in English letters only, convert it to small case letters  Mark all the letters that may change on a Turkish alphabet version. These letters are u, i, g, c, o, s.</li>

 <li>Ask your language model the probability of each possible sentence in Turkish character set. If there are N such letter in our sentence, then there are 2^N possible sentences.</li>

 <li>Choose the sentence with the highest probability.</li>

</ul>




Write a report of your findings on the performance of your language model. You should test all models that use different N values for N-Grams. In order to test your system, take some text from a source that uses Turkish alphabet. Convert this text to English alphabet version using the FST below, which will give you both versions of the same sentence.










What to submit to the Teams page

<ul>

 <li>Your source code</li>

 <li>Your report that includes your method details and your performance tables</li>

 <li>test run results for at least 20 sentences</li>

</ul>