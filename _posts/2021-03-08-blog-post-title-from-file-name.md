## Blog Post Title From First Header

Due to a plugin called `jekyll-titles-from-headings` which is supported by GitHub Pages by default. The above header (in the markdown file) will be automatically used as the pages title.

If the file does not start with a header, then the post title will be derived from the filename.

This is a sample blog post. You can talk about all sorts of fun things here.

---

### This is a header

#### Some T-SQL Code

```tsql
SELECT This, [Is], A, Code, Block -- Using SSMS style syntax highlighting
    , REVERSE('abc')
FROM dbo.SomeTable s
    CROSS JOIN dbo.OtherTable o;
```

#### Some PowerShell Code

```powershell
Write-Host "This is a powershell Code block";

# There are many other languages you can use, but the style has to be loaded first

ForEach ($thing in $things) {
    Write-Output "It highlights it using the GitHub style"
}
```
```python
import requests as r
import json
from bs4 import BeautifulSoup as bs
```

# 123
123 Heading


```python

```


```python
import requests

cookies = {
    '_ga': 'GA1.1.1915747621.1666529378',
    '.AspNetCore.Antiforgery.MUx3CiAbjnU': 'CfDJ8P3mjbCEhgJFh6JXrXC2MP4dgywFQXWjSeyfbCZz3LstCd_BPkh8BsQf3dP7TYRQbd8nPbBo-PXRMNRA7xzX5MYhFkq759wqeDoM3__U0DUASBQnMxae0IRJhAuoZa_rqGu16rEr6_r5ZTQx6f1p7yc',
    '_ga_7GJM164076': 'GS1.1.1668206151.9.1.1668206393.0.0.0',
}

headers = {
    'authority': 'www.taxdatahub.com',
    'accept': 'application/json, text/javascript, */*; q=0.01',
    'accept-language': 'en-US,en;q=0.9',
    'content-type': 'application/json; charset=UTF-8',
    # Requests sorts cookies= alphabetically
    # 'cookie': '_ga=GA1.1.1915747621.1666529378; .AspNetCore.Antiforgery.MUx3CiAbjnU=CfDJ8P3mjbCEhgJFh6JXrXC2MP4dgywFQXWjSeyfbCZz3LstCd_BPkh8BsQf3dP7TYRQbd8nPbBo-PXRMNRA7xzX5MYhFkq759wqeDoM3__U0DUASBQnMxae0IRJhAuoZa_rqGu16rEr6_r5ZTQx6f1p7yc; _ga_7GJM164076=GS1.1.1668206151.9.1.1668206393.0.0.0',
    'origin': 'https://www.taxdatahub.com',
    'referer': 'https://www.taxdatahub.com/6229fbf0ce4aef911f9de7bc/Essex%20County?town=0701',
    'requestverificationtoken': 'CfDJ8P3mjbCEhgJFh6JXrXC2MP5UHxBsSyEzOHp0ZTG-BKCbCrMIK7LmQmKv1CMGy6FKxkLL-TBY0jJ-3Eons0fWwthxldXD9jGrMtcDj4hPItRS9VP8q7qPlLeL5_6ryOwkuSJ1L_CuQIsagdqreKKgH1k',
    'sec-ch-ua': '"Google Chrome";v="107", "Chromium";v="107", "Not=A?Brand";v="24"',
    'sec-ch-ua-mobile': '?0',
    'sec-ch-ua-platform': '"macOS"',
    'sec-fetch-dest': 'empty',
    'sec-fetch-mode': 'cors',
    'sec-fetch-site': 'same-origin',
    'user-agent': 'Mozilla/5.0 (Macintosh; Intel Mac OS X 10_14_6) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/107.0.0.0 Safari/537.36',
    'x-requested-with': 'XMLHttpRequest',
}

json_data = {
    'searchTerm': {
        'From': 0,
        'MuniCodes': [
            '0701',
        ],
        'Phrase': '*',
        'BLQs': [],
        'ClassCodes': [],
        'Class4Codes': [],
        'SaleStartDate': '2022-10-12T21:39:36.159Z',
        'SaleEndDate': '2022-11-11T22:39:36.164Z',
        'OwnerName': '',
        'PropertyLocation': '',
        'SalePriceFrom': None,
        'SalePriceTo': None,
        'IncludeAdditionalLots': False,
        'Sort': 0,
    },
                       
    'gRecaptchaToken': "03AEkXODCMwtYd-lJqb3YMbsgxWpmFj1302TwWYE2YZvJ7f5KKFlcX0i3YLpejeV6Rb1hZ1kgM8N2FAMhaUb2JR87sBW9DP_qsxqMrBfDCTUIxSyFDviluj1N9c9Q66ke5_-el1k9anU-meBTGE49LowjggODDs1m4c-WHFOkWxFDnXkSgPJQ4iKNXqb0uY75kxTXaYS4osD92QSg_opBv5xBLQXrMIe8A3aRRgR2tPB0B2EZUvUfjQhUIkjlX0KGWQsSmBw-ojvtdp7jBySwoJtfxJOzo6srNsW8DzdN4iiCssnVjtQo154NEXh7aLS74gYHWAH2Ra9cGGQqvhj0f0cE-Me77sjoNc3KKlGWJlwyh_ar-oc4uJkqYJw1VtlcdOX1IYPJyedGVoh0ZmdQHjZtQWqKvAolRwikz8zbWPjujwuHQhXh2Phg9_wKP5YMM8n3Zx8ayepdkpR0dykZSzeolByG9QnLg5EcxPI2I8XJ4fXzxcyir7BI1aABaMzpep_-_t8PTmkVQ4UuaLnCixpMBZNqWW6bX-9rNoy3UoB8DRiQLOTvTHYR_5RF8muj2BaiNnrTjig5MDMhPnHyeo19_hQONJATBj9wxgxoWPZcd-fWtc6HqVl4IvgrZ4EImnqLG6CaefqHq1FnUIGcP6_8Lfaa_lBtDKvRJHVwa8lGpuIVhX5_8B9bHWJSNcEcrGkTdU_prA3eo8bzMm2bhImyiOP1ZyBztREKO2PD0uBxJlODUtBSaitrShlcNquWC4mmmYRy71IgVsGCIWAZnyZa8D4mf8I8cNeNvSURAlREoXiqvIBBYSYqXVe5e2RODncrzBu7C70f0iagnurKnxnpMm6eqaHxonBLxvIf057DpnKr5Qcvf_HClQpPQRd1RualBkdE7b04uQpZ5Z742-KJTyQeYTjhX7uwdgJtiBl84ULidWtTpFLH82H_4yEKxnd4fGeON5AGExACeYDjTwjlmA7gT9XnO7LfwRiwho9tyoWNWz8z_bGnv6x_Jd0TnXZ5nW4BlpIaCZ4OG7smydmHio6dCiRKiaJl9QxiGyicXt8CSNzzJ4F5UCDdkBWy6ZoMIm8LZE9Q7P7s6leyksG33VoJe8k7wRl52lu0GB7paf18PwVeSNWVLceeBLjVFUislS4VtrXLdB14PCFOqF3A4CIEp3my87ZxkiyBFOfGDb_M0_Sf3u__hWONSRjxer4z9ZBESqlFhws_VxHLFwckm0asIDMbWjfrxyOQdvMRqjraRtm3rkh8TXmjRrRLHMx-hDUnr6-_5"
}

response = requests.post('https://www.taxdatahub.com/search/6229fbf0ce4aef911f9de7bc/ExportExcel', cookies=cookies, headers=headers, json=json_data)
```


```python
response
```




    <Response [200]>




```python
response.content
```




    b'{"IsError":true,"StatusMsg":"Possible BOT detected!"}'




```python
res = r.get('https://www.taxdatahub.com/6229fbf0ce4aef911f9de7bc/Essex-County-Property-Assessment%20Search%20Hub/details?id=0701_8503_37')

res
```




    <Response [200]>




```python
soup = bs(res.content,'html.parser')
soup.text
```




    '\n\n\n\n\n\n\nDetails - [0701_8503_37] - Essex County Property Assessment Search Hub\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n\n'




```python

```