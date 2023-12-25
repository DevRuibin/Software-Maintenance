# 1.Introduction

1. Why does IT project fail so often?

   Software failure are usually predictable and avoidable, but organizations don't see preventing failures as important,
   even though they can harm or destroy the organization. Another reason is designing a maintainable software is hard as
   it
   is difficult to foresee all potential changes.

2. Define and explain, in your own words,the difference between software maintenance and software evolution.

   > Software maintenance is the process of modifying a software system or component after delivery to correct faults,
   > improve performance or other attributes, or adapt to a changed environment.

   Software maintenance typically doesn't evolve major changes to the system's architecture. Changes are implemented
   by modifying existing components and adding new components to the system.

   Software evolution is a broader term that encompasses both software maintenance and big changes.

   They are happening at different software life cycle. Software Evolution may arise:

    <list>
    <li>
    during software development
    </li>
    <li>
    during software maintenance
    </li>
    <li>
    when the system's continuous evolution made it too complex to maintain
    </li>
    </list>

3. List and explain the different types of software maintenance. Give an illustrative example of at least three
   different types of particular maintenance activities.

   <table style="both">
      <tr>
         <td>Why & WHEN</td>
         <td>Correction</td>
         <td>Enhancement</td>
      </tr>
      <tr>
         <td>Proactive</td>
         <td>Preventive</td>
         <td>Perfective</td>
      </tr>
      <tr>
         <td>Reactive</td>
         <td>Corrective</td>
         <td>Adaptive</td>
      </tr>
   </table>

   <tabs>
      <tab title="Preventive">
          Prevent problems before they occur
          <list>
             <li>
               Fix a bug that may crash the system for a very specific situation that may occur in the future
             </li>
          </list>
      </tab>
      <tab title="Perfective">
         Improve the performance, maintainability or other attributes of computer systems.
         <list>
            <li>
               Better input form
            </li>
            <li>
               Shortcut commnds
            </li>
         </list>
      </tab>
      <tab title="Corrective">
         Make a program usable in a changed environment.
         <list>
            <li>
            Often occurs after deployment when customers detect problems that were not discovered during initial testing of the system
            </li>
         </list>
      </tab>
      <tab title="Adaptive">
         Correct the faults in software and hardware.
         <list>
         <li>
            An insurance company decides to offer a new kind of insurance.
         </li>
         <li>
            A company decides to introduce a new sub system which needs to be integrated to the existed system.
         </li>
         </list>
      </tab>
   </tabs>

4. Discuss the need for, and give possible reasons for software maintenance, change and evolution.

   <tabs>
   <tab title="maintenance">
      <list type="decimal"> 
      <li>
      Changed user requirements
      </li>
      <li>
      Bug fixes
      <list>
      <li>
      scheduled routine fixes</li>
      <li>
      Emergence fixes</li>
      </list>
      </li>
      <li>
      Changed data formats
      </li>
      <li>
      Hardware changes
      </li>
      <li>
      Efficiency improvements
      </li>
      </list>
   </tab>
   <tab title="change">
      <list>
         <li>
            New requirements emerge when software is being used, even is being developed
         </li>
         <li>
            Business environment change
         </li>
         <li>
            <i>Feedback loop:</i> the changed software may even be the reason why the software changes
         </li>
         <li>
            Errors must be repaired
         </li>
         <li>
            New computers and equipment are added to the system
         </li>
         <li>
            The performance or reliability of the system may have to be improved
         </li>
         <li>
            New technology: new OS, new software versions
         </li>
      </list>
   </tab>
   <tab title="evolution">
      Software Evolution may arise:
       <list>
       <li>
         during software development where the design evolves and matures as the understanding of the problems to be solved,
         and how to solve it gradually increases.
       </li>
       <li>
         during software maintenance in the continuing process of adapting the system to the changing needs of its users 
         and usage environment after development.
       </li>
       <li>
         when the system's continuous evolution made it too complex to maintain, as the system may require a more extensive
         restructuring, redesign or even a full reimplementation or replacement.
       </li>
    </list>
   </tab>
   </tabs>

5. Give some main causes of maintenance problems.
   
   1. Poor quality of software documentation
   2. Poor software quality(unstructured code; too large components; inadequate design)
   3. Insufficient knowledge about the system and its domain
   4. Ineffectiveness of maintenance team(low productivity; low motivation; low skill levels; competing demands for programmer time.)
   
   <note>
    <b>competing demands for programmer time</b> refers to a situation where programmers, or software developers, face multiple tasks or responsibilities that require their attention and time, often simultaneously. 
   </note>

6. What is software ageing, why does software age and what are its consequences?

   1. what is software ageing
      
      software aging is the tendency for software to fail or cause a system failure after running continuously for a certain time, or because of ongoing changes in systems surrounding the software.
   
   2. why does software age 

      1. Maintenance activities
      2. Ignorant surgery and architectural erosion
      3. Inflexibility from the start
      4. Insufficient or inconsistent documentation
      5. Deadline pressure
      6. Duplicated functionality(code duplication)
      7. Lack of modularity

   3. what are its consequences

      When software ages, it tends to expand beyond the features initially planned and the phenomenon is scope creep.
      Scope Creep can be defined as <i>any change in project scope or pressure to deliver more than what was agreed
      customers and vendors initially.</i>

7. What is scope creep and how does it affect software quality?

    Scope Creep can be defined as <i>any change in project scope or pressure to deliver more than what was agreed
    customers and vendors initially.</i>

    Scope Creep is a common cause for the failure of software failures. It can occur in almost any software project, leading 
    to compromises in quality, delayed schedules, increased cost and decreased customers' satisfaction.

8. What different types of software evolution can be distinguished?

   <tabs>
   <tab title="Evolution Mechanisms">
      <list>
         <li>
            <b>Manual:</b> Changes are applied manually by a software developer
         </li>
         <li>
            <b>Generic:</b> Write sufficiently generic and abstract components that are broadly adaptable.
         </li>
         <li>
            <b>Generation: </b> Generate lower level representation from a higher-level specification of the software.
            <note>Vertical transformation or refinement: from more abstract to more accurate</note>
         </li>
         <li>
            <b>Transformation: </b> Old components are transformed into a new version.
            <note>Horizontal transformation or reconstructing: transformation at the same abstraction level.</note>
         </li>
         <li>
            <b>Configuration: </b> Different variants of a software components are available up front but the actual selection
            of which one to use is based on a desired configuration. For instance, OOP
         </li>
      </list>
   </tab>
   <tab title="Static and Dynamic">
      <list>
         <li>
            <b>Static evolution: </b> Changes are applied manually by human programmers. a part of the software gets adapted
            or replaced by a programmer and the evolved software is redeployed.
         </li>
         <li>
            <b>Dynamic evolution: </b> Dynamic evolution in software systems refers to the capability of a software 
            system to adapt, change, or evolve during runtime without the need for stopping and redeploying the system. This concept is particularly significant in environments where continuous availability is crucial, and in systems that must adapt to changing conditions or requirements in real-time.
            <note>
            self-adaptive systems, metaprogramming, context-oriented programming
            </note>
         </li>
      </list>
   </tab>
   </tabs>

9. Define and explain, in your own words, what technical debt is.

   Technical debt is an accumulation of poor and lazy implementation choices that slowly makes the code hard to maintain
   or evolve.

10. Pick one of the laws (1, 2, 6 or 7) of software evolution and explain it.

   <tabs>
   <tab title="1. Continuing change">
      A program that is used in a real-world environment must be continually adapted, or else become progressively less satisfactory.
      <list>
      <li>
      Evolution of the environment(Operational environment)</li>
      <li>
      Hence, increasing mismatch between the system and its environment</li>
      <li>
      Continuous need for change because requirements and environment continuously evolving
      </li>
      </list>
   </tab>
   <tab title="2. Increasing complexity">
      As a program is evolved its complexity increases with time unless specific work is done to maintain or reduce it.
      <list>
      <li>
      Inspired by the second law of entropy in thermodynamics</li>
      <li>
      Unaddressed technical debt increases entropy</li>
      <li>
      Small changes are applied in a step-wise process, each 'patch' makes senses locally, not globally.
      </li>
      <li>Effort needed to address accumulated technical debt. A more significant restructuring or refactoring may be needed.</li>
      </list>
   </tab>
   <tab title="6. Continuing growth">
      Functional content of a program must be continually increased to maintain users' satisfaction over its lifetime.
      <list>
      <li>
      Related to the first law, but with focus on functional requirements</li>
      <li>
      Often one cannot afford to omit existing functionality
         <note>
         Removing or significantly altering existing functionalities can disrupt the user's workflow and lead to dissatisfaction. Even if new features are added, the omission or degradation of existing ones can be seen as a step backward rather than an improvement.
         </note>
      </li>
      </list>
   </tab>
   <tab title="7.Declining quality">
      Evolving programs will be perceived as of declining quality unless rigorously maintained and adapted to a changing
      Operational environment.
      <list>
      <li>
      Related to the fist law, but with focus on observed reliability </li>
      </list>
   </tab>
   </tabs>