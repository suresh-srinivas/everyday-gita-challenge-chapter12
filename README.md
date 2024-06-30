# EveryDay G.I.T.A Challenge

I wanted to share the GitHub repository for the Everyday Gita Challenge - [GitHub Repo](https://github.com/suresh-srinivas/everyday-gita-challenge-chapter12).

## To contribute and send Pull Requests (PRs):

### Fork the repository
Click on the "Fork" button at the top right of the repo page to create your own copy.

### Clone your fork
On your machine, clone your forked repository using the command:

```sh
git clone https://github.com/suresh-srinivas/everyday-gita-challenge-chapter12.git
```

### Create a branch
Before making any changes, create a new branch to work on. Use the command:

```sh
git checkout -b your-branch-name
```

### Make your changes
Implement your changes in the relevant files.

### To add new recordings, modify the \`index.html\` file as follows:

Add a new `<div class="participant">` section for each new participant. Use the following structure for each new participant:

```html
<div class="participant">
    <img src="ParticipantImage.jpeg" alt="Participant Name">
    <div>
        <strong>Participant Name</strong>
        <audio controls>
            <source src="ParticipantAudioFile.mp3" type="audio/mpeg">
            Your browser does not support the audio element.
        </audio>
    </div>
</div>
```

Replace `ParticipantImage.jpeg` with the actual image file name, `Participant Name` with the participant's name, and `ParticipantAudioFile.mp3` with the audio file name.

### Commit your changes
Once your changes are ready, commit them with a descriptive message:

```sh
git add .
git commit -m "Added new recordings for [Participant Names]"
```

### Push to your fork
Push your changes to your forked repository using:

```sh
git push origin your-branch-name
```

### Open a Pull Request
Go to the original repository on GitHub and click on "Compare & pull request." Select your branch and create a pull request with a clear description of what you've done.
"""

