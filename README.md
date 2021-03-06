# LinkedIn-Resume-Parser

Usage:
`python linkedin_scraper.py /path/to/docx`

Gives you:
```python
response = {
  'name': 'name',
  'email': 'email',
  'experience': [{
    'post': '',
    'company': '',
    'description': '',
    'start_date': '',
    'end_date': '',
    'time_period': ''
    }],
  'education': [],
  'courses': [],
  'projects': [{
    'name': '',
    'start_date': '',
    'end_date': '',
    'description': ''
    }],
  'certifications': [],
  'skills': [],
  'patents': [{
    'name': '',
    'id': '',
    'description': ''
    }],
  'languages': [],
  'honors': [{
    'title': '',
    'issuer': '',
    'description': ''
    }],
  'organizations': [],
  'other': ''
}
```

To export your LinkedIn profile as PDF:
1. Click the Me icon at the top of your LinkedIn homepage and select View profile, or navigate to someone else's profile.
2. Click the  More icon in the top section of the profile, to the right of the picture.
3. Select  Save to PDF.
4. The PDF file will be downloaded and saved to the default download location on your computer. Once you open the file, you can print it.


To convert PDF as DOCX:
1. Visit [pdf2docx.com](pdf2docx.com)
2. Upload PDF
3. Click Convert
4. Download DOCX file

# LICENSE

Copyright (c) 2017 Samkit Jain

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
