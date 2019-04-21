# colab


##Colaboratory
Frequently Asked Questions
What is Colaboratory?
Colaboratory is a research tool for machine learning education and research. It’s a Jupyter notebook environment that requires no setup to use.

What browsers are supported?
Colaboratory works with most major browsers, and is most thoroughly tested with desktop versions of Chrome and Firefox.

Is it free to use?
Yes. Colaboratory is a research project that is free to use.

What is the difference between Jupyter and Colaboratory?
Jupyter is the open source project on which Colaboratory is based. Colaboratory allows you to use and share Jupyter notebooks with others without having to download, install, or run anything on your own computer other than a browser.

How is this related to colaboratory.jupyter.org?
In 2014 we worked with the Jupyter development team to release an early version of the tool. Since then Colaboratory has continued to evolve, guided by internal usage.

Where are my notebooks stored, and can I share them?
All Colaboratory notebooks are stored in Google Drive. Colaboratory notebooks can be shared just as you would with Google Docs or Sheets. Simply click the Share button at the top right of any Colaboratory notebook, or follow these Google Drive file sharing instructions.

If I share my notebook, what will be shared?
If you choose to share a notebook, the full contents of your notebook (text, code, and output) will be shared. You can omit code cell output from being saved or shared by selecting Edit > Notebook settings > Omit code cell output when saving this notebook. The virtual machine you’re using, including any custom files and libraries that you’ve setup, will not be shared. So it’s a good idea to include cells which install and load any custom libraries or files that your notebook needs.

Can I import an existing Jupyter/IPython notebook into Colaboratory?
Yes. Choose "Upload notebook" from the File menu.

What about Python3? (or R, Scala, ...)
Colaboratory supports Python 2.7 and Python 3.6. We're aware that users are interested in support for other Jupyter kernels (eg R or Scala). We would like to support these, but don't yet have any ETA.

How can I search Colaboratory notebooks?
Use Drive's search box. Clicking on the Colaboratory logo at the top left of the notebook view will show all notebooks in Drive. You can also search for notebooks that you have opened recently using File->Open Recent.

Where is my code executed? What happens to my execution state if I close the browser window?
Code is executed in a virtual machine dedicated to your account. Virtual machines are recycled when idle for a while, and have a maximum lifetime enforced by the system.

How can I get my data out?
You can download any Colaboratory notebook that you’ve created from Google Drive following these instructions, or from within Colaboratory’s File menu. All Colaboratory notebooks are stored in the open source Jupyter notebook format ( .ipynb).

How may I use GPUs and why are they sometimes unavailable?
Colaboratory is intended for interactive use. Long-running background computations, particularly on GPUs, may be stopped. Please do not use Colaboratory for cryptocurrency mining. Doing so is unsupported and may result in service unavailability. We encourage users who wish to run continuous or long-running computations through Colaboratory’s UI to use a local runtime.

How can I reset the virtual machine(s) my code runs on, and why is this sometimes unavailable?
The "Reset all runtimes" entry in the "Runtime" menu will return all managed virtual machines assigned to you to their original state. This can be helpful in cases where a virtual machine has become unhealthy e.g. due to accidental overwrite of system files, or installation of incompatible software. Colaboratory limits how often this can be done to prevent undue resource consumption. If an attempt fails please try again later.

Why does drive.mount() sometimes fail saying "timed out", and why do I/O operations in drive.mount()-mounted folders sometimes fail?
Google Drive operations can time out when the number of files or subfolders in a folder grows too large. If thousands of items are directly contained in the top-level "My Drive" folder then mounting the drive will likely time out. Repeated attempts may eventually succeed as failed attempts cache partial state locally before timing out. If you encounter this problem, try moving files and folders directly contained in "My Drive" into sub-folders. A similar problem can occur when reading from other folders after a successfuldrive.mount(). Accessing items in any folder containing many items can cause errors like OSError: [Errno 5] Input/output error (python 3) or IOError: [Errno 5] Input/output error (python 2). Again, you can fix this problem by moving directly contained items into sub-folders.
Note that "deleting" files or subfolders by moving them to the Trash may not be enough; if that doesn't seem to help, make sure to also Empty your Trash.

I found a bug or have a question, who do I contact?
Open any Colaboratory notebook. Then go to the Help menu and select ”Send feedback...”.

Why prompt to enable third-party cookies?
Colaboratory uses HTML iframes and service workers hosted on separate origins in order to display rich outputs securely.
Browsers require enabling third-party cookies to use the service workers within iframes.
An alternative to enabling third-party cookies for all sites is to whitelist the following hostname in your browser settings: googleusercontent.com.


## Links to datasets
- https://github.com/zalandoresearch/fashion-mnist
- https://github.com/rois-codh/kmnist