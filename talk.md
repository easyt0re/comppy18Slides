# A Data Pre-processing Script for PyTorch 
# Machine Learning Problem

## Yang Wang

KTH ITM

---

layout: false

# Overview

- ## Background
- ## Implementation
	- ## Class
	- ## Testing
	- ## Documentation
- ## Outcome
- ## Discussion

---

# Background

- ## Challenge in Modeling
- ## Course Material
- ## Machine Learning with PyTorch

---

# Implementation

- ## Class (Dataset, Transform)
- ## Testing (Travis-CI, Coverall)
- ## Documentation (ReadtheDocs)

---

# Implementation - Class

```python
class ForKinDataset(Dataset):
	def __init__(self, csv_JS, csv_WS, root_dir, transform=None):
		return ForKinDataset

	def __len__(self):
		return lengthOfDataset

	def __getitem__(self, idx):
		return sample

class ToTensor(object):
	def __call__(self, sample):
		return transformedDict
```

- ## "structure" class vs. function class

---

# Implementation - Testing

```python
@pytest.fixture(params=[1, 5, 7])
def sample_idx(request):
	return request.param

def test_item(sample_idx):

def test_trans_size(sample_idx):

def test_read_all():

```

- ## Testing Locally vs. with Travis-CI
	- ### MANY commits for small things
	- ### local Travis-CI?

---

# Implementation - Documentation

- ## NOT a string parser
- ## yml for ReadtheDocs
- ## MANY conventions and rules

---

# Outcome

- ## a [Github Project](https://github.com/easyt0re/comppy18Proj) for the Code
- ## a README page with the Project
- ## a Related [Travis-CI](https://travis-ci.org/easyt0re/comppy18Proj) Test
- ## a [Coverage](https://coveralls.io/github/easyt0re/comppy18Proj) Badge
- ## a [Documentation](https://readthedocs.org/projects/comppy18proj) hosted on ReadtheDocs
- ## a LaTeX Report based on the README
- ## a [Presentation](https://easyt0re.github.io/comppy18Slides) hosted on Github Page

---

# Discussion

- ## Python in General (indentation, version, index, assign)
- ## Time-consuming and Important
- ## Search for Documentation (mock, yml, ...)
