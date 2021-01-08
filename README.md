# COMP790: Deep Learning

Instructor: [Colin Raffel](http://colinraffel.com)

Term: Spring 2021

Meeting time: Mondays and Wednesdays, 12:30-1:45pm

Office hours: TBD

Deep learning is the branch of machine learning focused on training neural networks.
Neural networks have proven to be powerful across a wide range of domains and tasks, including computer vision, natural language processing, speech recognition, and beyond.
The success of these models is partially thanks to the fact that their performance tends to improve as more and more data is used to train them.
Further, there have been many advances over the past few decades that have made it easier to attain good performance when using neural networks.
In this course, we will provide a thorough introduction to the field of deep learning.
We will cover the basics of building and optimizing neural networks in addition to specifics of different model architectures and training schemes.
The course will closely follow the "[Dive into Deep Learning](https://d2l.ai/)" textbook and will have a standard lecture/homework/exam format.

## Prerequisites

Students need to have taken the following courses:
  - Machine learning (one of COMP562, COMP755, STOR565, or equivalent)
  - Linear algebra (one of MATH210, MATH347, MATH577, or equivalent)
  - Multivariate calculus (one of MATH233, MATH522, or equivalent)
  
Further, it is recommended that students have some basic familiarity with statistical concepts.
Finally, students must be proficient in reading and writing Python code.

## Schedule

Note that since this is the first time this class is being taught, we may deviate from this schedule somewhat if things take significantly longer or shorter to get through.
Students should read the associated textbook section/chapters before class.
All readings refer to corresponding sections in [Dive into Deep Learning](http://d2l.ai).

| Date            | Subject                                                        | Reading                | Homework              |
| --------------- | -------------------------------------------------------------- | ---------------------- | --------------------- |
| Wed, 1/20       | Class introduction, background, logistics                      | §2.1-2.7 (optional)    | H1 assigned           |
| Mon, 1/25       | Linear regression                                              | §3.1-3.3               |                       |
| Wed, 1/27       | Logistic regression                                            | §3.4-3.7               | H1 due, H2 assigned   |
| Mon, 2/1        | Multilayer perceptrons                                         | §4.1-4.3               |                       |
| Wed, 2/3        | Under/overfitting, regularization                              | §4.4-4.6               | H2 due, H3 assigned   |
| Mon, 2/8        | Backpropagation, numerical stability                           | §4.7-4.8               |                       |
| Wed, 2/10       | Convolutional neural networks 1                                | §6.1-6.3               | H3 due                |
| Mon, 2/15       | Wellness day, no class                                         | —                      |                       |
| Wed, 2/17       | Convolutional neural networks 2                                | §6.4-6.6               | H4 assigned           |
| Mon, 2/22       | Batch normalization & residual connections                     | §7.5-7.6               |                       |
| Wed, 2/24       | Sequence models and language                                   | §8.1-8.3               | H4 due, H5 assigned   |
| Mon, 3/1        | Recurrent neural networks 1                                    | §8.4-8.7               |                       |
| Wed, 3/3        | Recurrent neural networks 2                                    | §9.1-9.4               | H5 due                |
| Mon, 3/8        | Midterm Review                                                 | —                      |                       |
| Wed, 3/10       | Midterm                                                        | —                      | H6 assigned           |
| Mon, 3/15       | Sequence-to-sequence learning                                  | §9.5-9.8               |                       |
| Wed, 3/17       | Attention 1                                                    | §10.1-10.4             | H6 due, H7 assigned   |
| Mon, 3/22       | Attention 2                                                    | §10.5-10.7             |                       |
| Wed, 3/24       | Gradient descent                                               | §11.1-11.5             | H7 due, H8 assigned   |
| Mon, 3/29       | Adaptive gradient methods                                      | §11.6-11.11            |                       |
| Wed, 3/31       | Multi-accelerator training                                     | §12.5-12.7             | H8 due, H9 assigned   |
| Mon, 3/29       | Data augmentation and transfer learning for CV                 | §13.1-13.2             |                       |
| Wed, 3/31       | Word vectors                                                   | §14.1-14.7             | H9 due                |
| Mon, 4/5        | Wellness day, no class                                         | —                      |                       |
| Wed, 4/7        | Transfer learning for NLP                                      | §14.8-14.10, 15.6-15.7 | H10 assigned          |
| Mon, 4/19       | Generative adversarial networks                                | §13.10, 17.1-2         |                       |
| Wed, 4/21       | Autoencoders & variational autoencoders                        | —                      | H10 due, H11 assigned |
| Mon, 4/26       | Deep autoregressive models                                     | —                      |                       |
| Wed, 4/28       | Semi-supervised and self-supervised learning                   | —                      | H11 due               |
| Mon, 5/3        | Distribution shift; fairness, accountability, and transparency | §4.9                   |                       |
| Wed, 5/5        | Final exam review                                              | —                      |                       |
| Final exam slot | Final exam                                                     | —                      |                       |

## Grading

  1. **Homework**, 55 points: There will be 11 homework assignments. Each homework assignment will be assigned on Wednesday and due the following Wednesday. We will skip the assignments that fall over a wellness day. Homework will consist of some combination of math and coding. Each homework is worth 5 points.
  1. **Midterm**, 15 points: The midterm will take place on 3/8 and will cover all topics discussed before the midterm.
  1. **Final Exam**, 30 points: The final exam will take place during our scheduled final exam slot and will cover all topics discussed in the class.

## Late work and the honor code

You can replace your worst homework grade with a perfect grade (5/5), which effectively excuses you from a single homework.
I can grant you an extension on a homework due to a life emergency, but you must request an extension at least 24 hours before the homework is due.

All students are expected to follow the guidelines of the [UNC honor code](http://honor.unc.edu).
In the context of this class, it is particularly important that you cite the source of different ideas, facts, or methods and do not claim someone else's work as your own.
If you are unsure about which actions violate that honor code, feel free to ask me.

## Conduct

I ask that we all follow the [NeurIPS Code of Conduct](https://nips.cc/public/CodeOfConduct) and the [Recurse Center Social Rules](https://www.recurse.com/social-rules).
I value the perspectives of individuals from all backgrounds reflecting the diversity of our students.
I broadly define diversity to include race, gender identity, national origin, ethnicity, religion, social class, age, sexual orientation, political background, and physical and learning ability.
I will strive to make this classroom an inclusive space for all students.
Please let me know if there is anything I can do to improve.

Acts of discrimination, harassment, interpersonal (relationship) violence, sexual violence, sexual exploitation, stalking, and related retaliation are prohibited at UNC-Chapel Hill.
If you have experienced these types of conduct, you are encouraged to report the incident and seek resources on campus or in the community.
Please contact the Director of Title IX Compliance/Title IX Coordinator (Adrienne Allison, adrienne.allison@unc.edu), Report and Response Coordinators (Ew Quimbaya-Winship, eqw@unc.edu; Rebecca Gibson, rmgibson@unc.edu; Kathryn Winn kmwinn@unc.edu), Counseling and Psychological Services (CAPs) (confidential) in Campus Health Services at (919) 966-3658, or the Gender Violence Services Coordinators (confidential) (Cassidy Johnson, cassidyjohnson@unc.edu; Holly Lovern, holly.lovern@unc.edu) to discuss your specific needs.
Additional resources are available at http://safe.unc.edu.

## Resources

The University of North Carolina at Chapel Hill facilitates the implementation of reasonable accommodations, including resources and services, for students with disabilities, chronic medical conditions, a temporary disability or pregnancy complications resulting in difficulties with accessing learning opportunities.
All accommodations are coordinated through the Accessibility Resources and Service Office. See the ARS Website for contact information: https://ars.unc.edu or email ars@unc.edu.
Relevant policy documents as they relate to registration and accommodations determinations and the student registration form are available on the ARS website under the About ARS tab.

CAPS is strongly committed to addressing the mental health needs of a diverse student body through timely access to consultation and connection to clinically appropriate services, whether for short or long-term needs. Go to their [website](https://caps.unc.edu/) or visit their facilities on the third floor of the Campus Health Services building for a walk-in evaluation to learn more.

## Changes

I reserve the right to make changes to the syllabus, including project due dates and test dates.
These changes will be announced as early as possible.
