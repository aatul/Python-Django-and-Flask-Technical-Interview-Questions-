# Python, Django and Flask Technical Interview Questions

Looking forward to appear in Python, Django and Flask Interview, here are the key 100+ Java Interview Questions with Answers only for you including some of the tricky questions with answers.

### Table of Contents
| Sr.No.        | Question      | 
| ------------- |-------------| 
| 1             |[What do you like about Python and what you dislike about it?](https://github.com/aatul/Python-Django-and-Flask-Technical-Interview-Questions-/blob/master/README.md#1-what-do-you-like-about-python-and-what-you-dislike-about-it) | 
| 2             |[What are major differences in Python 2.7 and 3.X](https://github.com/aatul/Python-Django-and-Flask-Technical-Interview-Questions-/blob/master/README.md#2-what-are-major-differences-in-python-27-and-3x) | 
| 3             |[What is a Python Dictionary?](https://github.com/aatul/Python-Django-and-Flask-Technical-Interview-Questions-/blob/master/README.md#3-what-is-a-python-dictionary) | 
| 4             |[What are map(), filter() and reduce() functions in Python?](https://github.com/aatul/Python-Django-and-Flask-Technical-Interview-Questions-/blob/master/README.md#4-what-are-map-filter-and-reduce-functions-in-python) | 
| 5             |[What is monkey patching and is it ever a good idea?](https://github.com/aatul/Python-Django-and-Flask-Technical-Interview-Questions-/blob/master/README.md#5-what-is-monkey-patching-and-is-it-ever-a-good-idea) | 
| 6             |[What is pickle?](https://github.com/aatul/Python-Django-and-Flask-Technical-Interview-Questions-/blob/master/README.md#6-what-is-pickle) | 
| 7             |[The basic structure of any Django app, what files are involved, and what are the components?](https://github.com/aatul/Python-Django-and-Flask-Technical-Interview-Questions-/blob/master/README.md#7-the-basic-structure-of-any-django-app-what-files-are-involved-and-what-are-the-components) | 
| 8             |[How would you add the app in the command line?](https://github.com/aatul/Python-Django-and-Flask-Technical-Interview-Questions-/blob/master/README.md#8-how-would-you-add-the-app-in-the-command-line) | 
| 9             |[What problem were you trying to solve when you used celery?](https://github.com/aatul/Python-Django-and-Flask-Technical-Interview-Questions-/blob/master/README.md#9-what-problem-were-you-trying-to-solve-when-you-used-celery) | 
| 10             |[How do you host your Django Application?](https://github.com/aatul/Python-Django-and-Flask-Technical-Interview-Questions-/blob/master/README.md#10-how-do-you-host-your-django-application) | 
| 11             |[In Django, can you describe me the top of the basic comprehension needed to present in view of the template?](https://github.com/aatul/Python-Django-and-Flask-Technical-Interview-Questions-/blob/master/README.md#11in-django-can-you-describe-me-the-top-of-the-basic-comprehension-needed-to-present-in-view-of-the-template) | 
| 12             |[Considering a file structure of a new application, what does it look like? How do you start a brand new project in Django?](https://github.com/aatul/Python-Django-and-Flask-Technical-Interview-Questions-/blob/master/README.md#12considering-a-file-structure-of-a-new-application-what-does-it-look-like-how-do-you-start-a-brand-new-project-in-django) | 


**[Back to Top](https://github.com/aatul/Python-Django-and-Flask-Technical-Interview-Questions-/blob/master/README.md#python-django-and-flask-technical-interview-questions)**

---

### 1. What do you like about Python and what you dislike about it?

**Likes:**
- Ease of interaction with other languages and platforms with 3rd party modules available in Python Package Index (PyPI). Also extensive support of libraries reduces the code writing effort significantly.
- Built in data structures and dynamic high level data typing allows faster implementation with less LoCs.
- Ease of learning and code redability because of its indentation oriented syntax.

**Dislikes:** 
- Speed- being an interpreted language, it is not best suited for time-critical tasks. 
- Multithreading - due to the Global Interpreter Lock.

**[Back to Top](https://github.com/aatul/Python-Django-and-Flask-Technical-Interview-Questions-/blob/master/README.md#python-django-and-flask-technical-interview-questions)**

---

### 2. What are major differences in Python 2.7 and 3.X

-	Division operator 
-	Print function
-	Unicode : In python 2.x implicit str type is ASCII, in 3.x its Unicode
-	Xrange: is range in 3.x
-	Error Handling: ‘as’ required in 3.x
-	input() instead of raw_input()
-	from __future__ import division : allows to work 2.x as 3.x division operator

**[Back to Top](https://github.com/aatul/Python-Django-and-Flask-Technical-Interview-Questions-/blob/master/README.md#python-django-and-flask-technical-interview-questions)**

---

### 3. What is a Python Dictionary?

It is an unordered collection of items. A dictionary element has 2 components, a key and a value associated with it.

**[Back to Top](https://github.com/aatul/Python-Django-and-Flask-Technical-Interview-Questions-/blob/master/README.md#python-django-and-flask-technical-interview-questions)**

---

### 4. What are map(), filter() and reduce() functions in Python?

**map():** It takes another function as a parameter along with a sequence of iterables and returns an output after applying the function to each iterable present in the sequence. 

Syntax:
```python
map(function, iterables) 
```

**filter():** The filter() function is used to create an output consisting of values for which the function returns true.

Syntax: 
```python
filter(function, iterables)
```

**reduce():** The reduce(fun,seq) function is used to apply a particular function passed in its argument to all of the list elements mentioned in the sequence passed along. This function is defined in “functools” module.

**[Back to Top](https://github.com/aatul/Python-Django-and-Flask-Technical-Interview-Questions-/blob/master/README.md#python-django-and-flask-technical-interview-questions)**

---

### 5. What is monkey patching and is it ever a good idea?

Monkey patch refers to dynamic modifications of a class or module at run-time.

Common applications of monkey patching are:
- To extend or modify the behavior of third-party or built-in libraries or methods at runtime without touching the original code.
- During testing mock the behavior of libraries, modules, classes, or any objects.
- To quickly fix some issues if we do not have the time or resources to roll out a proper fix to the original software.

**[Back to Top](https://github.com/aatul/Python-Django-and-Flask-Technical-Interview-Questions-/blob/master/README.md#python-django-and-flask-technical-interview-questions)**

---

### 6. What is pickle?

It is used for serializing and de-serializing a Python object structure. Any object in python can be pickled so that it can be saved on disk. What pickle does is that it “serializes” the object first before writing it to a file. Pickling is a way to convert a python object (list, dict, etc.) into a character stream. 

**[Back to Top](https://github.com/aatul/Python-Django-and-Flask-Technical-Interview-Questions-/blob/master/README.md#python-django-and-flask-technical-interview-questions)**

---

### 7. The basic structure of any Django app, what files are involved, and what are the components?

![Basic structure of Django application](https://user-images.githubusercontent.com/649439/176218443-9a4e6335-7d70-4f83-b8cd-df8a906efb2d.png)

Above is the basic structure of any Dkango application.

**[Back to Top](https://github.com/aatul/Python-Django-and-Flask-Technical-Interview-Questions-/blob/master/README.md#python-django-and-flask-technical-interview-questions)**

---

### 8. How would you add the app in the command line?

```python
python manage.py startapp [app name]
```
Use above command

**[Back to Top](https://github.com/aatul/Python-Django-and-Flask-Technical-Interview-Questions-/blob/master/README.md#python-django-and-flask-technical-interview-questions)**

---

### 9. What problem were you trying to solve when you used celery?

Celery is an asynchronous task queue/job queue based on distributed message passing. It is focused on real-time operation but supports scheduling as well.

The execution units, called tasks, are executed concurrently on a single or more worker server using multiprocessing, Eventlet, or gevent. Tasks can execute asynchronously (in the background) or synchronously (wait until ready).

Celery allows you to execute tasks outside of your Python app so it doesn't block the normal execution of the program

**[Back to Top](https://github.com/aatul/Python-Django-and-Flask-Technical-Interview-Questions-/blob/master/README.md#python-django-and-flask-technical-interview-questions)**

---

### 10. How do you host your Django Application?

- Install necessary packages.
- Initial server setups.
- Preparing our Django app for production.
- Setting up gunicorn.
- Setting up nginx.

**[Back to Top](https://github.com/aatul/Python-Django-and-Flask-Technical-Interview-Questions-/blob/master/README.md#python-django-and-flask-technical-interview-questions)**

---

### 11.	In Django, can you describe me the top of the basic comprehension needed to present in view of the template?

Django provides a convenient way to generate dynamic HTML pages by using its template system.

A template consists of static parts of the desired HTML output as well as some special syntax describing how dynamic content will be inserted.

**[Back to Top](https://github.com/aatul/Python-Django-and-Flask-Technical-Interview-Questions-/blob/master/README.md#python-django-and-flask-technical-interview-questions)**

---

### 12.	Considering a file structure of a new application, what does it look like? How do you start a brand new project in Django?

```python
django-admin startproject [project name]
```

Use above command

**[Back to Top](https://github.com/aatul/Python-Django-and-Flask-Technical-Interview-Questions-/blob/master/README.md#python-django-and-flask-technical-interview-questions)**

---
