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

---

# Implementation - Documentation

---

# Outcome

- ## a Github Project for the Code
- ## a README page with the Project
- ## a Related Travis-CI Test
- ## a Coverage Badge
- ## a Documentation hosted on ReadtheDocs
- ## a LaTeX Report based on the README
- ## a Presentation hosted on Github Page

---

