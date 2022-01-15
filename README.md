### Hi there 👋

<!--
**MendiburuFrancisco/MendiburuFrancisco** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

class MendiburuFrancisco(self):
        self.username = 'MendiburuFrancisco'
        self.name = 'Francisco Mendiburu'
        self.web = 'https://mendiburufrancisco.github.io' 
        self.linkedin = 'https://linkedin.com/in/mendiburufrancisco/'
        self.source = {
            'born': ['Argentina','Mercedes','Corrientes'],
            'Where I live': ['Rosario','Santa Fe'],
        },
        self.studies = {
            'student': ['System engineer','UTN Rosario'],
        },

        

    def __str__(self):
        return self.name


if __name__ == '__main__':
    me = MendiburuFrancisco()
