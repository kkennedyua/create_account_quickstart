<!---

Images can be added in-line as a reStructured text substitution, but will not render in markdown. See reStructured text example. http://docutils.sourceforge.net/docs/ref/rst/restructuredtext.html#substitution-definitions

|CyVerse logo|

--->

# Create an Account and Add Services
<!---
Use short, imperative titles e.g. Upload and share data, uploading and sharing data
--->

## Goal

<!---
Avoid covering upstream and downstream steps that are not explicitly and necessarily part of the tutorial - write or link to separate quick starts/tutorials for those parts
--->

<!---
A few sentences (50 words or less) describing the ultimate goal of the steps in this tutorial
--->

This Quick Start walks you through the steps to creating a CyVerse account. Your CyVerse account gives you access to several different apps and services, including the Discovery Enviroment and the CyVerse Wiki, which contains how-to information, and subscribes you to that service's email notifications about maintenance periods and outages, and to CyVerse's newsletter, _Node_.

In addition, there are other CyVerse services, such as Atmosphere and BisQue, to which you may request access.

---

### Register for an account
<!---
This content pulled from [Create Account](http://www.cyverse.org/learning-center/create-account)
--->

1. To register for a CyVerse account, go to the [CyVerse user management portal](https://user.cyverse.org/).
2. Complete the information on the form. 

.. Hint:: Use an institutional email address if you intend to add access to [Atmosphere](http://www.cyverse.org/atmosphere), CyVerse's cloud-computing platform.

3. Click the link in the email you receive to validate your email and begin using your account.

### Add additional services
<!---
This content pulled from webpage [Manage Services](http://www.cyverse.org/learning-center/manage-account)
--->

In addition to the default services that are provided to you when you sign up for a new account, you can request access to others. For more information on the list of all CyVerse apps and platforms, see the CyVerse [Products](http://www.cyverse.org/products) web page.

1. Go to the [CyVerse user management portal](https://user.cyverse.org/), click **Login** at the top, and enter your CyVerse username and password.

2. In the **Available Services** section at the bottom of the Apps & Services tab, find the app or service to add, and then click **Request Access**.

3. Repeat for each service to add.

4. If requesting access to Atmosphere, specify the instance size, including the number of CPUs, memory in GB, and root storage in GB, needed for your instance. 

	**Start small.** Start with the smallest size until you know for certain which size you need. You can always size up but you can't size down.

.. note:: 
	If you did not use an institutional email address (as required by Atmosphere), you will need to [change your email address](http://www.cyverse.org/learning-center/manage-account#ChangeEmail).

5. When the service has been added, you will receive an email with access instructions and may begin using the service. 

### Summary

<!---
Summary a--->

**Next Steps:**

1. CyVerse offers a variety of different platforms for your computational needs. You may want to begin by reading the Quick Start for each platform.
2. Using data at CyVerse is an important part of the CyVerse experience. Learn more here **_Link needed to QS guide, Share Data with Other Users_**.

|Platform|Interface|Link|Platform Documentation|Quick Start|
|--------|---------|----|----------------------|-----------|
|Discovery Environment|Web/Point-and-click|[Discovery Environment](https://de.iplantcollaborative.org)|[Manual](https://wiki.cyverse.org/wiki/display/DEmanual/Table+of+Contents)|[Quick Start]()|
|Atmosphere|Command-line (ssh) and/or Desktop (VNC)|[Atmosphere](https://atmo.cyverse.org)|[Manual](https://wiki.cyverse.org/wiki/display/atmman/Atmosphere+Manual+Table+of+Contents)|[Quick Start]()|
|BisQue|Web/Point-and-click and/or Command-line (API)|[BisQue](http://bisque.iplantcollaborative.org/client_service)|[Manual](https://wiki.cyverse.org/wiki/display/BIS)|[Quick Start]()|
|DNA Subway|Web/Point-and-click|[DNA Subway](http://dnasubway.iplantcollaborative.org/)|[Manual](http://dnasubway.iplantcollaborative.org/files/pdf/DNA_Subway_Guide.pdf)|[Quick Start]()|
|Agave API|Command-line (API)|[Agave API](https://agaveapi.co)|[Live Docs](https://agaveapi.co)|[Quick Start]()|


## More help and additional information

<!---
Short description and links to any reading materials
--->

- **Search for an answer:** [CyVerse Learning Center](http://www.cyverse.org/learning-center) or [CyVerse Wiki](https://wiki.cyverse.org)
- **Post your question to the user forum:** [Ask CyVerse](http://ask.cyverse.org/questions)

### Fix or improve this tutorial 

- **Fix this tutorial on GitHub:** [GitHub](FIX_THIS_IN_YOUR_DOCUMENTATION)
- **Send a note:** [Tutorials@CyVerse.org](mailto:Tutorials@CyVerse.org)

<!---

SAMPLE DIRECTIVES (DELETE UNUSED ONES)
--------------------------------------

See: http://docutils.sourceforge.net/docs/ref/rst/directives.html#admonitions

.. Danger::
	This step is dangerous

.. Important::
	This step is important
	
.. Caution::
	Exercise caution
	
.. Hint::
	This is a hint

.. Important::
	This is very important

.. note:: This is a note admonition.
   This is the second line of the first paragraph.

   - The note contains all indented body elements
     following.
   - It includes this bullet list.



.. |CyVerse logo| image:: ./img/cyverse_rgb.png
    :width: 500
    :height: 100
--->
