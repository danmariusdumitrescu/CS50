# CS50
---
metadata:
    display_name: Checkboxes
    markdown: |
       Checkbox problems allow learners to select multiple options. Learners can see all the options along with the problem text.
      
       When you add the problem, be sure to select Settings to specify a Display Name and other values that apply.
       You can use the following example problem as a model.
       >>The following languages are in the Indo-European family:<<
       [x] Urdu
       [ ] Finnish
       [x] Marathi
       [x] French
       [ ] Hungarian
       Note: Make sure you select all of the correct options—there may be more than one!
       [explanation]
       Urdu, Marathi, and French are all Indo-European languages, while Finnish and Hungarian are in the Uralic family.
       [explanation]
data: |
      <problem>
        <p>Checkbox problems allow learners to select multiple options. Learners can see all the options along with the problem text.</p>
        <p>When you add the component, be sure to select <strong>Settings</strong> 
        to specify a <strong>Display Name</strong> and other values that apply.</p>
        <p>You can use the following example problem as a model.</p>
          <p>The following languages are in the Indo-European family:</p>
          <choiceresponse>
            <checkboxgroup>
              <choice correct="true" name="urdu">Urdu</choice>
              <choice correct="false" name="finnish">Finnish</choice>
              <choice correct="true" name="marathi">Marathi</choice>
              <choice correct="true" name="french">French</choice>
              <choice correct="false" name="hungarian">Hungarian</choice>
            </checkboxgroup>
          </choiceresponse>
        <p><strong>Note</strong>: Make sure you select all of the correct options—there may be more than one!</p>
        <solution>
         <div class="detailed-solution">
             <p>Explanation</p>
             <p>Urdu, Marathi, and French are all Indo-European languages, while Finnish and Hungarian are in the Uralic family.</p> 
          </div>
        </solution>
      </problem>
