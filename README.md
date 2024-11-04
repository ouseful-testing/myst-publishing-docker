# OUseful publishing framework tests

Docker container for publishing notebooks and md using:

- jupyter-book / sphinx;
- myst;
- latex;
- OUseful OU-XML tools etc

Aim:

- mount a directory with source files into container and generate output OU-XML, preview (branded) PDF, HTML ebook, maybe docx
- should be able to notebooks referencing popular scientific pyhton packages out of the can;
- convert OU-XML to MyST md/notebooks;
- generate OU-XML that bundles additional html5.zip files where required (eg JupyterLite and WebR builds).

Maybe also a tool for building OU VLE html5.zip bundles for JupyterLite (pyhton and R; eg demo with: TM112, M348, maybe even chunks of TM351+pglite?)
