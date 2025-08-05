# ZLT-Corpus: Zambian Languages Translation Corpus

The Zambian Languages Translation Corpus (ZLT-Corpus) is a crowdsourced translation project dedicated to creating and maintaining high-quality bilingual corpora for Zambian languages. This repository serves as a collaborative hub for collecting, translating, and refining these valuable linguistic resources using the powerful combination of Git and OmegaT.

Our goal is to build a comprehensive and reliable dataset that can be used for various natural language processing (NLP) applications, including machine translation, language modeling, and linguistic research. By leveraging the collective knowledge of native speakers and language enthusiasts, we aim to preserve and promote Zambian languages in the digital age.

## How to Participate

Contributing to the ZLT-Corpus is a straightforward process. Follow these steps to get started:

### 1. Install Git and Create a GitHub Account

* **Install Git:** If you don't have Git installed, follow the official installation instructions for your operating system: [Git Installation Guide](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
* **Create a GitHub Account:** If you don't have a GitHub account, sign up for one here: [GitHub Sign Up](https://github.com/join)

### 2. Link Your GitHub Account with Git using SSH

To securely access the project repositories, you'll need to set up an SSH key. This is a one-time process that authenticates your computer with your GitHub account.

* **Generate an SSH Key:** Follow the instructions in the official GitHub documentation to generate a new SSH key: [Generating a new SSH key](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)
* **Add your SSH Key to GitHub:** Once you've generated the key, follow these steps to add it to your GitHub account: [Adding a new SSH key to your GitHub account](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account)

### 3. Start the SSH Agent

OmegaT needs to be able to access the repository without requiring your password every time. The SSH agent helps with this by securely managing your keys.

* **Start the `ssh-agent` and add your key:** Follow these instructions to start the SSH agent and add your newly created key: [Using SSH agent with OmegaT](https://omegat.org/documentation/wiki/SSH_agent_and_OmegaT)

### 4. Install OmegaT

OmegaT is a free, open-source computer-assisted translation (CAT) tool that we use for collaborative translation.

* **Download and Install OmegaT:** Get the latest version of OmegaT from the official website: [OmegaT Download](https://omegat.org/en/downloads)

### 5. Open the Project in OmegaT

**Important:** Do not clone the repository directly using Git. Instead, open the project within OmegaT to ensure proper synchronization and collaboration.

* In OmegaT, go to `Project` > `Download Team Project...`
* Enter the SSH link for the language pair you wish to work on. You'll find a list of available projects below.
* The project might take a while to download the first time, depending on its size and your internet connection.

## Best Practices for Translation

To ensure a smooth and collaborative workflow, please follow these guidelines:

* **Start Online:** Always open the project in OmegaT while connected to the internet. This ensures that your local files are updated with the latest translations from other contributors.
* **Translate Online:** OmegaT automatically synchronizes your translations with the remote repository every three minutes while you are connected to the internet. This helps to prevent conflicts and keeps the project up-to-date.
* **Close Online:** When you are finished with a translation session, close the project while still connected to the internet. This ensures that any unsynced changes are pushed to the repository.
* **Offline Work:** You can still work on the project offline. The changes will be synchronized the next time you connect to the internet and open the project.
* **Saving:** Use `Ctrl + S` to save your progress within OmegaT. **Do not use the `Commit` function in OmegaT's Git integration** as the automatic synchronization handles this for you.

## Available Projects

Here is a list of the available language pairs you can contribute to.

1.  **English to Chitonga:** [zlt-corpus-EnTo](git@github.com:your-username/zlt-corpus-EnToi.git)

## Future Plans

We are continuously working to improve the ZLT-Corpus project. Our future plans include:

* **Moses SMT Integration:** Integrating a Moses Statistical Machine Translation (SMT) system to provide translation suggestions and improve the quality and speed of translation.
