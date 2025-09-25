function checkAnswerStarTriangle() {
    const outerloop = document.getElementById('outerLoop').value.toLowerCase().replace(/\s/g,'');
    const spaceloop = document.getElementById('spaceLoop').value.toLowerCase().replace(/\s/g,'');
    const starloop = document.getElementById('starLoop').value.toLowerCase().replace(/\s/g,'');

    const resultDiv = document.getElementById('result');
    const resultText = document.getElementById('resultText');

    //expected answers
    const correctouterloop = ['int i = 1; i <= n; i++', 'int i = 1; i <= 5; i++', 'i = 1; i <= n; i++', 'i = 1; i <= 5; i++'];
    const correctspaceloop = ['int j = 1; j <= n - i; j++', 'int j = 1; j <= 5 - i; j++', 'j = 1; j <= n - i; j++', 'j = 1; j <= 5 - i; j++'];
    const correctstarloop = ['int j = 1; j <= 2 * i - 1; j++', 'j = 1; j <= 2 * i - 1; j++', 'int j = 1; j <= (2 * i) - 1; j++'];

    var score = 0;
    var feedback = [];

    if(correctouterloop.some(ans => outerloop === ans.toLowerCase().replace(/\s/g,''))) {
        console.log('Outer loop is correct');
        score += 1;
        feedback.push('✅ First loop is correct!');
    }
    else {
        console.log('Outer loop is incorrect');
        feedback.push('❌ First loop is incorrect!');
    }
    if(correctspaceloop.some(ans => spaceloop === ans.toLowerCase().replace(/\s/g,''))) {
        console.log('space loop is correct');
        score += 2;
        feedback.push('✅ Second loop is correct!');
    }
    else {
        console.log('space loop is incorrect');
        feedback.push('❌ Second loop is incorrect!');
    }
    if(correctstarloop.some(ans => starloop === ans.toLowerCase().replace(/\s/g,''))) {
        console.log('star loop is correct');
        score += 3;
        feedback.push('✅ Third loop is correct!');
    }
    else {
        console.log('star loop is incorrect');
        feedback.push('❌ Third loop is incorrect!');
    }

    if(score === 6) {
        resultDiv.style.background = 'linear-gradient(135deg, #27ae60 0%, #2ecc71 100%)';
        resultText.innerHTML =`
            Congratulations 🎉<br>
            <br>
            Score: 3/3
            <br>
            <br>
            <img src="assets/goldenticket.jpeg" alt="Golden Ticket" >
        `
    }
    else{
        resultText.innerHTML =`
            Try Again!<br>
            <br>
            ${feedback[0]}<br>
            ${feedback[1]}<br>
            ${feedback[2]}<br>
        `
        feedback = [];
    }

    resultDiv.classList.add('show');
}


function InvertedStarTriangle() {
    const outerloop = document.getElementById('outerLoop2').value.toLowerCase().replace(/\s/g,'');
    const spaceloop = document.getElementById('spaceLoop2').value.toLowerCase().replace(/\s/g,'');
    const starloop = document.getElementById('starLoop2').value.toLowerCase().replace(/\s/g,'');

    const resultDiv2 = document.getElementById('result2');
    const resultText2 = document.getElementById('resultText2');

    //expected answers
    const correctouterloop2 = ["int i = n; i >= 1; i--","i = n; i >= 1; i--","int i = 1; i <= n; i++","int i = 1; i <= 5; i++","i = 1; i <= n; i++","i = 1; i <= 5; i++"];
    const correctspaceloop2 = ["int j = i; j < n; j++"," j = i; j < n; j++","int j = 1; j <= n - i; j++","int j = 1; j <= 5 - i; j++","j = 1; j <= n - i; j++","j = 1; j <= 5 - i; j++"];
    const correctstarloop2 = ["int j = 1; j <= (2 * i - 1); j++"," j = 1; j <= (2 * i - 1); j++","int j = 1; j <= 2 * i - 1; j++","j = 1; j <= 2 * i - 1; j++","int j = 1; j <= (2 * i) - 1; j++"];

    var score2 = 0;
    var feedback2 = [];

    if(correctouterloop2.some(ans => outerloop === ans.toLowerCase().replace(/\s/g,''))) {
        console.log('Outer loop is correct');
        score2 += 1;
        feedback2.push('✅ First loop is correct!');
    }
    else {
        console.log('Outer loop is incorrect');
        feedback2.push('❌ First loop is incorrect!');
    }
    if(correctspaceloop2.some(ans => spaceloop === ans.toLowerCase().replace(/\s/g,''))) {
        console.log('space loop is correct');
        score2 += 2;
        feedback2.push('✅ Second loop is correct!');
    }
    else {
        console.log('space loop is incorrect');
        feedback2.push('❌ Second loop is incorrect!');
    }
    if(correctstarloop2.some(ans => starloop === ans.toLowerCase().replace(/\s/g,''))) {
        console.log('star loop is correct');
        score2 += 3;
        feedback2.push('✅ Third loop is correct!');
    }
    else {
        console.log('star loop is incorrect');
        feedback2.push('❌ Third loop is incorrect!');
    }

    if(score2 === 6) {
        resultDiv2.style.background = 'linear-gradient(135deg, #27ae60 0%, #2ecc71 100%)';
        resultText2.innerHTML =`
           Congratulations 🎉<br>
            <br>
            Score: 3/3
            <br>
            <br>
            <img src="assets/goldenticket.jpeg" alt="Golden Ticket" >
        `
    }
    else{
        resultText2.innerHTML =`
            Try Again!<br>
            <br>
            ${feedback2[0]}<br>
            ${feedback2[1]}<br>
            ${feedback2[2]}<br>
        `
        feedback2 = [];
    }

    resultDiv2.classList.add('show');
}
