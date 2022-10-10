# Natalya Makarenko

## Contact Info

**Address**: Astana, Kazakhstan

**Email address**: <natmkaz@gmail.com>

**Phone number (Telegram)**: +7 707 77 66 313

## About Me

I am a programmer with extensive experience in the industry. 

I became interested in blockchain technology in my last year of Masters and wrote my master's thesis on this
topic - "Document Authentication using Blockchain: Diploma Validation as a Test Case". Frontend is a necessary part of developing DApps, and this is one of the reasons why I am taking this course.

## Skills

- Delphi (during undergraduate studies and after)
- C, Java (while studying for a master's degree)
- Python (NumPy, Pandas...), Flask
- Master Degree: Computer Vision, Deep Learning, Algorithmic Trading...
- Blockchain: Solidity, Web3.js and Web3.py
- HTML, CSS, JavaScript

## Code Example

In the user part for the project Blockchain + IoT (Python, Flask):

    @app.route('/', methods=['GET','POST'])                      
    def index():
        if request.method == 'POST':
            sensoList = request.form.get("sensoList")
            inputLow = request.form.get("inputLow")
            inputHigh = request.form.get("inputHigh")

            if len(inputLow)==0 or len(inputHigh)==0:
                flash('Please enter both thresholds','warning')
                return redirect(request.url)

            if float(inputLow) > float(inputHigh):
                flash('The lower threshold must not be greater than the upper threshold!','warning')
                return redirect(request.url)

            middleware_thresholds_send(sensoList, float(inputLow), float(inputHigh))

            flash('Threshold values have been applied!','success')
            return redirect(request.url)

        return render_template('index.html')

## Work Experience 

- **[02/2020 – 09/2020]** [The Group of companies «Fuel and Energy complex – KAZAKHSTAN»](https://www.tek-kaz.kz/en)
  - Chief Manager of the Department of Automation and Maintenance of Production and Information Technologies 
- **[07/2016 – 11/2019]** Benatech LLP
  - Lead engineer of Automated Control Systems 
- **[01/2010 – 07/2016]** [Kazakhstan Aluminium Smelter JSC (KAS)](https://www.erg.kz/en)
  - Lead engineer of the Telemechanics and Automated Control Systems group

## Education

- **[08/2020 – 05/2022]** [Nazarbayev University](https://nu.edu.kz/)
  - Master of Science in Computer Science
- **[12/2021]** [Authorized by University at Buffalo, The State University of New York and offered through Coursera](http://coursera.org/verify/KXEYPFZ3CMQ3)
  - Online non-credit course: Blockchain Basics
- **[12/2017]** [Netcontrol Oy](http://www.netcontrol.com)
  - Training: Netcon 3000 Advanced Maintenance
- **[09/2006 – 05/2010]** [Innovative University of Eurasia](https://www.ineu.kz/en/)
  - Bachelor of Science in Information Systems
  
## Languages

- **Mother tongue**: Russian
- **Other language(s)**: English (IELTS 6.5 in 2019; and then 2 years of study for a Master in English)
