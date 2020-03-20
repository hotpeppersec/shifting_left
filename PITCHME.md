---?image=assets/img/light_left.jpeg
@title[Shifting Left]

@snap[east]
@img[](assets/img/title.png)
@snapend

Note:

- You can **follow along** with this talk on my github (hotpeppersec).
- There are links throughout the presentation that you can click on for greater detail.
- I realize this presentation is currently a bit wonky when viewed on a mobile device.
  - I'm working on it, don't @ me.
- My speaking style is fairly informal and if you stop me with a question I will do my best to answer it.

---?image=assets/img/black_and_blue.jpeg
@title[Bio]

@snap[west]
@img[span-50](assets/img/us.jpg)
@snapend

@snap[north-east span-45 text-08]
@box[bg-purple text-yellow](Current#Consulting Engineer at Palo Alto Networks)
@snapend

@snap[east span-45]
@box[bg-blue text-yellow text-08](Previous#Motorola<br>R&D Eng at Nokia Siemens<br>SecDataSci [@SecureCloudDev](https://twitter.com/SecureCloudDev))
@snapend

@snap[south-east span-45 text-08]
@box[bg-pink text-yellow](Education#MS DePaul University<br>MS Northwestern<br>BS in Comp Sci)
@snapend

Note:

- CE gets called in to assist SE's as a subject matter expert.
- Tech Lead in cellular base station product dev at Moto.
- Bought out by NSN
- Wound up at Salesforce doing security data science.
  - Use ML to deal with 1B security logs per day.
- MS in network eng, network security

---?image=assets/img/light_left.jpeg
@title[What]

@snap[north-west span-100 text-20 text-bold text-right text-orange]
Shift What?
@snapend

@snap[south-west span-200 text-left text-08 text-orange]
@ul[circles](true)

- Address bugs and issues at the earliest.
  - Resolve issues sooner than w/traditional methods.
- Early amalgamation of security concerns and dev concerns.
  - Not always (never?) the same set of goals!

@ulend
@snapend

Note:

- we often hear that sec is **everyones responsibility**

---?image=assets/img/light_left.jpeg
@title[Uniformity]

@snap[north-west span-100 text-20 text-bold text-right text-orange]
Uniformity
@snapend

@snap[south-west span-200 text-right text-08 text-orange]
@ul[circles](false)

- Your situation is not so unique that you qualify for an exception.
- Drive out fragmented security process.
  - Security tends to vary by application/location/team.
  - Disparate systems contribute to gaps in network security posture.
- Avoid looking at "slices" of traffic or applications.
  - Go for holism.

@ulend
@snapend

---?image=assets/img/light_left.jpeg
@title[Agile]

@snap[north-west span-100 text-20 text-bold text-right text-orange]
Leverage Agile Practices
@snapend

---?image=assets/img/light_left.jpeg
@title[Heavy]

@snap[north-west span-100 text-20 text-bold text-left text-orange]
Beware the Heavy Hand
@snapend

---?image=assets/img/light_left.jpeg
@title[Scrutiny]

@snap[north-west span-100 text-20 text-bold text-left text-orange]
Open it Up
@snapend

@snap[south-west span-200 text-left text-08 text-orange]
@ul[circles](false)

- Document your processes.
- Open Source your tools.
- Solicit feedback and scrutiny.

@ulend
@snapend

---?image=assets/img/light_left.jpeg
@title[UseIt]

@snap[north-west span-100 text-20 text-bold text-left text-orange]
Master the Tools!
@snapend

---?image=assets/img/light_left.jpeg
@title[Testing]

@snap[north-west span-100 text-20 text-bold text-left text-orange]
More Testing!
@snapend

@snap[south-west span-200 text-left text-08 text-orange]
@ul[circles](false)

- Everyone understands testing, conceptually.
  - Very few are following through!
- Monitor the percentage of test coverage.
- Create unit & functional tests to keep coverage high.

@ulend
@snapend

@snap[span-50]
![us](assets/img/sec-test.jpg)
@snapend

---?image=assets/img/light_left.jpeg
@title[Policy]

@snap[north-west span-100 text-20 text-bold text-right text-orange]
Have a Plan!
@snapend

@snap[south-west span-200 text-left text-08 text-orange]
@ul[circles](false)

- Things never turn out the way we envision them. Stuff Happens.
- Folks need to know how to reach you/your team with issues.
- For GitHub.com, [use of SECURITY.md for example](https://github.com/hotpeppersec/shifting_left/security/policy).

@ulend
@snapend

@snap[span-50]
![wurst](assets/img/wurst.jpeg)
@snapend

---?image=assets/img/light_left.jpeg
@title[CI]

@snap[north-west span-100 text-20 text-bold text-left text-orange]
Automate Checks via CI
@snapend

---?image=assets/img/light_left.jpeg
@title[Red]

@snap[north-west span-100 text-20 text-bold text-left text-orange]
Fun for the Red Team Too!
@snapend

@snap[south-west span-200 text-left text-08 text-orange]
@ul[circles](false)

- [Testing Red Team Infra](https://blog.xpnsec.com/testing-redteam-infra/)
- [Offensive Dev with GitHub Actions](https://www.mdsec.co.uk/2020/03/offensive-development-with-github-actions/)

@ulend
@snapend

---?image=assets/img/light_left.jpeg
@title[Thank You]

@snap[north-west span-100 text-20 text-bold text-center text-orange]
Thank You
@snapend

@snap[south-west span-200 text-left text-08 text-orange]
@ul[circles](false)

- [GitPitch Slide Decks for Developers](https://gitpitch.com/pricing)
- The @gitlink[source for these slides is available here](shifting_left) on my GitHub account (@hotpeppersec)
- All the folks who took time to review and provide feedback!

@ulend
@snapend

@snap[midpoint]
![Thank You](https://media.giphy.com/media/3oKIPfFs4hPHemcU6I/giphy.gif)
@snapend
