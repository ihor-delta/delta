© 2023 Ihor Budko (Ihor Delta)

In compliance with [Freedoms](https://github.com/ihor-delta/freedoms)

*Important Clarification:* Freedom Of Transition and Freedom Of Ignorance is ignored by these Apps

Syntax: text/json

{
  description: "CI apps"
  mode: disabled, 
  exceptions:{
    @Freedoms: {
      mode: enabled,
      description: "in complience with the Freedoms"
    },
    @TLKAE: {
      mode: enabled
      description: "The Last King And Emperor" 
    },
    @Insights: {
      mode: {
        global: disabled,
        exceptions: {
          @IhorBudko: enabled
        }
      }
    },
    @Obraz: {
      mode: enabled,
      link: "https://obraz.io/"
    }
  }
}
