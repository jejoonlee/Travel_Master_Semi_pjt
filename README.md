# ๐งโ๐ป ์ต์ข ํ๋ก์ ํธ 1

[์ต์ข ํ๋ก์ ํธ URL](https://github.com/jejoonlee/Travel_Master_Semi_pjt)

[def search](#%EF%B8%8F-def_search)

- [pagination ๊ธฐ๋ฅ](#pagination-๊ธฐ๋ฅ)
- [search ๊ธฐ๋ฅ](#search-๊ธฐ๋ฅ)
- [์ธ๊ธฐ๊ฒ์์ด ๊ธฐ๋ฅ](#์ธ๊ธฐ๊ฒ์์ด-๊ธฐ๋ฅ)
- [Arrange ๊ธฐ๋ฅ](#arrange-๊ธฐ๋ฅ)

[๋น๋๊ธฐ](#EF%B8%8F-๋น๋๊ธฐ)

- [๋๊ธ ๋น๋๊ธฐ](#๋๊ธ-๋น๋๊ธฐ)
- [๋๊ธ ์ญ์  ๋น๋๊ธฐ](#๋๊ธ-์ญ์ -๋น๋๊ธฐ)
- [๋๊ธ ์์  ๋น๋๊ธฐ](#๋๊ธ-์์ -๋น๋๊ธฐ)

[ํ๋ก์ ํธ in PPT](#%EF%B8%8F-ํ๋ก์ ํธ-in-PPT)



## โ๏ธ ํ๋ก์ ํธ ํ๊ณ ๋์ ๋๋ ๊ฒ

> ์์ง ๋ง์ด ๋ถ์กฑํ ๊ฒ ๊ฐ๋ค. ๊ทธ๋๋ ์๋ก ์๋ํ ๊ธฐ๋ฅ์ด ๊ตฌํ์ด ๋๋ฉด, ์ ๋ง ๋ฟ๋ฏํ๋ค. ์ด ๋ง์ผ๋ก ๊ฐ๋ฐ์ ํ๋ ๊ฒ ๊ฐ๋ค.
>
> ๊ทธ๋ฆฌ๊ณ  ๋ค๋ฅธ ๋ถ์ ์ฝ๋๋ฅผ ๋ณด๋ฉฐ ์ดํดํ๊ณ , ์ ๋ฆฌ๋ฅผ ํ๋ฉฐ ๋ง์ด ๋ฐฐ์ ๋ค. ์ถํ์ ํ๋ก์ ํธ ๋์, ๋ค์ ๋ณด๋ฉฐ ์ฝ๋๋ฅผ ์ง๋ด์ผ ํ  ๊ฒ ๊ฐ๋ค.
>
> ์ด๋ฒ์๋ ๋๋ณด๋ค ํจ์ฌ ์ ํ๋ ๋ถ์ด ์์ด์, ๊ทธ ๋ถํํ ๋ง์ด ์์งํ ๊ฒ์ด ๋ง๋ค. ํ์ง๋ง ๋ค์ ํ๋ก์ ํธ๋ ์ ๋ง ๋ฐฐ๋ก ์ด์ฌํ ํด์ผ ํ  ๊ฒ ๊ฐ๋ค. (์ผ๋จ ์ํ์ด ๋๋๋ฉด, ์ํ๊ณต๋ถ ํ๋ ์๊ฐ์ ๋ ๊ฐ๋ฐ์ ์ ๊ฒฝ์ ์ธ ๊ฒ์ด๋ค.)



## โ๏ธ ํ๋ก์ ํธ ํ๋ฉด์ ํ์ตํ ๊ฒ

### โ๏ธ API

> #### Application Protocol Interface
>
> ํ๋ฐํธ๊ฐ ํ๋ฉด์์ ๋ณด์ด๋ ๊ฒ ๋ค์ด๊ณ , ๋ฐฑ์ ํด๋น ์๋ฒ์์ ํ์ํ ๋ฐ์ดํฐ์ด๋ค.
>
> - Front์์ Back์ผ๋ก ์ ๋ณด๋ฅผ ์์ฒญํ๊ณ , Back ์ ๋ณด๋ฅผ ์ฐพ์ Front์ ๋ณด๋ด๋ฉด, Front์์ ํด๋น ์ ๋ณด๋ฅผ ๋ณด์ฌ์ค๋ค
> - Front์์ Back์ผ๋ก ์ ๋ณด๋ฅผ ํน์ ํ ๊ท์น์ ๋ง์ถฐ ์ ๊ณตํ๋ ๊ฒ์ด API์ด๋ค.
>
> Open API
>
> - Open API๋ฅผ ์ฌ์ฉํ๋ ๊ฒ์, ์ด๋ฏธ ๋ง๋ค์ด์ง ๋ฐ์ดํฐ๋ค์, ๋ฐ์ดํฐ๋ค์ ์ ๊ณตํ๋ ์ฌ์ดํธ์ ๊ธฐ์ค์ ๋ง์ถฐ์ ์ฌ์ฉํ๋ ๊ฒ์ด๋ค
>   - ์์๋ก **์ง๋, ๊ฒฐ์ , ์ฑํ, AI** ๊ฐ ์๋ค

### โ๏ธ from django.db.models import Q

> ์ฃผ๋ก `.filter` ORM์ ์ฌ์ฉํ  ๋, ์ด๋ ํ ์ ๋ณด๋ฅผ ์ฐพ์ ๋ ์ฌ์ฉํ๋ค
>
> ์ฃผ๋ก `| & ^` ๋ฅผ ์ฌ์ฉํ๋ค (์์๋๋ก, and, or, xor)
>
> ์์)
>
> ORM : `Q(question__startswith='Who') | Q(question__startswith='What')`
>
> SQL : `WHERE question LIKE 'Who%' OR question LIKE 'What%'`

### โ๏ธ def search

> ### Search์ ๋ชจ๋ธ

```python
class Search(models.Model):
    # ๊ฒ์ํ  ๋, ๋ฐ๋ ํ๋
    title = models.CharField(max_length=10)
    # ๊ฒ์์ด๋ฅผ ์ํด ํ์ํ ํ๋
    count = models.PositiveIntegerField(default=0)
```



> ### views.py (์ ์ฒด๋ฅผ ๊ฐ์ง๊ณ  ์จ ๊ฒ)

```python
def search(request):
    popular_list = {}
    if request.method == "GET":
        search = request.GET.get("searched", "")
        sort = request.GET.get("sorted", "")
        
        if not search.isdigit() and not search == "":
            if Review.objects.filter(
                Q(title__icontains=search)
                | Q(content__icontains=search)
                | Q(place__icontains=search)
            ):
                popular_list[search] = popular_list.get(search, 0) + 1

        for k, v in sorted(popular_list.items(), key=lambda x: -x[1]):
            if Search.objects.filter(title=k):
                s = Search.objects.get(title=k)
                s.count += 1
                s.save()
            else:
                s = Search(title=k, count=v)
                s.save()
        popular = Search.objects.order_by("-count")[:10]

        search_list = Review.objects.filter(
            Q(title__icontains=search)
            | Q(content__icontains=search)
            | Q(place__icontains=search)
            | Q(theme__icontains=search)
            | Q(user_id__profile_name__icontains=search)
        )

        if search:
            if search_list:
                pass

            if sort == "pop":
                search_list = search_list.order_by("-like_users")
                sort="pop"
                print(search_list)

            if sort == "recent":
                search_list = search_list.order_by("-updated_at")
                sort="recent"
                print(search_list)

            page = int(request.GET.get("p", 1))
            pagenator = Paginator(search_list, 5)
            boards = pagenator.get_page(page)

            return render(
                request,
                "articles/search.html",
                {
                    "search": search,
                    # ํ์ด๋ณ๋ก ์ ์ฅ๋ queryset์ ๊ฐ์ง๊ณ  ์จ๋ค
                    "boards": boards,
                    # ๊ฒ์์ด์ ๋ํ, ๊ฒ์๋ queryset๋ค์ ๋ฆฌ์คํธ๋ฅผ ๊ฐ์ง๊ณ  ์จ๋ค
                    "search_list": search_list,
                    # ๊ฒ์์ด ๋ง์ด ๋ ์์ผ๋ก queryset์ ์ ๋ฆฌํด์ ๊ฐ์ง๊ณ  ์จ๋ค
                    "popular": popular,
                    # ํน์  ํ๋๋ก ์ธํด ์ ๋ ฌ๋ queryset๋ค์ ๊ฐ์ง๊ณ  ์จ๋ค
                    "sort" : sort,
                },
            )
        else:
            k = "๊ฒ์ ๊ฒฐ๊ณผ๊ฐ ์์ต๋๋ค ๋ค์ ๊ฒ์ํด์ฃผ์ธ์"
            context = {"v": k}
            return render(request, "articles/searchfail.html", context)
```



#### pagination ๊ธฐ๋ฅ

> ํ์ด์ง๋ฅผ ๋๋๋ ๊ธฐ๋ฅ

```python
from django.core.paginator import Paginator

page = int(request.GET.get("p", 1))
pagenator = Paginator(search_list, 5)
boards = pagenator.get_page(page)
```

- `from django.core.paginator import Paginator` ๋ฅผ ํตํด์ `Paginator` ๋ชจ๋์ ๊ฐ์ง๊ณ  ์จ๋ค
- `page = int(request.GET.get("p", 1))` 
  - client๊ฐ ์์ฒญํ url์ `p`, ํ์ด์ง์ ๋ณ์๋ฅผ ๊ฐ์ง๊ณ  ์จ๋ค (์ฌ๊ธฐ์ ๊ธฐ๋ณธ ์ค์ ์ 1์ด๋ค)
- `pagenator = Paginator(search_list, 5)`
  - `search_list`๋ ๊ฒ์ํด์ ๋ฐ์ queryset๋ค์ ๋ฆฌ์คํธ๋ค์ ๋ณ์ ๋ช์ด๋ค (search ๊ธฐ๋ฅ์์ ํ์ธ ๊ฐ๋ฅ)
  - `search_list`๋ฅผ ํ ํ์ด์ง ๋น 5๊ฐ์ฉ ๊ฐ์ง๊ณ  ์จ๋ค
- `boards = pagenator.get_page(page)`
  - `pagenator`์ ์ ์ฅํ queryset๋ค (์ฌ๊ธฐ์ 5๊ฐ)๋ฅผ ๊ฐ์ง๊ณ  ์จ๋ค
  - `pagenator`๋ ๊ฐ ํ์ด์ง ๋น 5๊ฐ์ฉ ์ ์ฅ์ด ๋์ด ์๊ณ , url์์ ๋ถ๋ฌ์จ `p`์ ๊ฐ์ `boards`์ ์ ์ฅํ๋ค
- ๐๐๐**์ฆ `page`๋ ์ ์ ๊ฐ ์์ฒญํ ๋ช ๋ฒ์งธ ํ์ด์ง โ `pagenator`๋ ๊ฐ ํ์ด์ง ๋น ๋ช๊ฐ์ queryset์ ์ ์ฅํ ์ง ์ง์  โ `boards`๋ ์ ์ ๊ฐ ์์ฒญํ ํ์ด์ง์ queryset๋ค์ ๊ฐ์ง๊ณ  ์จ๋ค**

##### **search.html**

```html
<div class="row mt-2">
  <div class="col-12 my-5">
    <nav aria-label="Page navigation example">
      <ul class="pagination justify-content-center">
        {% if boards.has_previous %}
          <li class="page-item">
            <a class="page-link" href="?searched={{ search }}&sorted={{ sort }}&p={{ boards.previous_page_number }}">์ด์ </a>
          </li>
        {% else %}
          <li class="page-item disabled">
            <a class="page-link" href="#">์ด์ </a>
          </li>
        {% endif %}
        <li class="page-item">
          <a class="page-link" href="#">{{ boards.number }}
            /
            {{ boards.paginator.num_pages }}</a>
        </li>
        {% if boards.has_next %}
          <li class="page-item">
            <a class="page-link" href="?searched={{ search }}&sorted={{ sort }}&p={{ boards.next_page_number }}">๋ค์</a>
          </li>
        {% else %}
          <li class="page-item disabled">
            <a class="page-link" href="#">๋ค์</a>
          </li>
        {% endif %}
      </ul>
      </nav>
    </div>
  </div>
```

-  `href="?searched={{ search }}&sorted={{ sort }}&p={{ boards.previous_page_number }}"`
  - `a` ํ๊ทธ์ ํฌํจ๋ ๋งํฌ
  - ํด๋น ๋งํฌ๋ฅผ ํด๋ฆญํ๋ฉด ์ง๊ธ ํ์ด์ง์ ์ด์  ํ์ด์ง์ ์ ๋ณด๋ฅผ ๊ฐ์ง๊ณ  ์จ๋ค
  - ์) ํ๊ตญ์ ๊ฒ์ํ๊ณ , ์ธ๊ธฐ์์ผ๋ก ์ ๋ ฌํ, 2๋ฒ์งธ ํ์ด์ง๋ฅผ ์ฐพ์๊ฐ๊ธฐ
    - `/?search='ํ๊ตญ'&sorted=popular&p=2 `
    - ์ฌ๊ธฐ์ ๋ง์ฝ์ ์ ๋ ฌ์ด ์์ผ๋ฉด `sort=`์ผ๋ก ๊ทธ๋ฅ ๋์ด๊ฐ๋ค



#### search ๊ธฐ๋ฅ

```python
def search(request):
    if request.method == "GET":
        search = request.GET.get("searched", "")

        search_list = Review.objects.filter(
            Q(title__icontains=search)
            | Q(content__icontains=search)
            | Q(place__icontains=search)
            | Q(theme__icontains=search)
            | Q(user_id__profile_name__icontains=search)
        )

        if search:
            if search_list:
                pass
            
            return render(
                request,
                "articles/search.html",
                {
                    "search": search,
                    "boards": boards,
                    "search_list": search_list,
                    "popular": popular,
                    "sort" : sort,
                },
            )
        else:
            k = "๊ฒ์ ๊ฒฐ๊ณผ๊ฐ ์์ต๋๋ค ๋ค์ ๊ฒ์ํด์ฃผ์ธ์"
            context = {"v": k}
            return render(request, "articles/searchfail.html", context)
```

- `search = request.GET.get("searched", "")`
  - `search` ๋ณ์๋, client๊ฐ `searched` url์ ์์ฒญ ํ์ ๋, ๊ฒ์ํ ๊ฐ์ ์ ์ฅํ๋ค
  - ์ฌ๊ธฐ์ `("searched", "")`์์ ""๋, ์์ ๊ฐ์ ๋ฃ๋ ๊ฒ
    - url ์์) `/?searched=๊ฒ์ํ ๋จ์ด`

```python
from django.db.models.import Q

search_list = Review.objects.filter(
        Q(title__icontains=search)
        | Q(content__icontains=search)
        | Q(place__icontains=search)
        | Q(theme__icontains=search)
        | Q(user_id__profile_name__icontains=search)
    )
```

- `search` ๋ณ์์ ๊ฐ์ด ์ ์ฅ๋์์ผ๋ฉด, DB์์ ํด๋น ๊ฐ์ ํฌํจํ queryset์ ๊ฐ์ง๊ณ  ์จ๋ค
- `search_list = Review.objects.filter`, Review๋ผ๋ DB์์ quaryset๋ค์ ๊ฐ์ง๊ณ  ์์ `search_list`์ ์ ์ฅํ๋ค
  - get์ ํ๋์ queryset๋ง ์ฐพ์ ์ ์์ผ๋ฉฐ, filter๋ ๊ทธ ์ด์์ผ๋ก ์ฐพ์ ์ ์๋ค
- `Q(title__icontains=search)` 
  - Review์ title์ด๋ผ๋ ํ๋ ์์, `search` ๋ณ์์ ๊ฐ์ ํฌํจ(`icontains`)ํ๋ฉด search_list์ ์ ์ฅํ๊ธฐ
  - ์ฌ๊ธฐ์ Q๋ ์์ ์ค๋ช์ด ์์ (import์ ํด์ผ ํ๋ค)



 #### ์ธ๊ธฐ๊ฒ์์ด ๊ธฐ๋ฅ

> search์ ์ ์ฅ๋ ๊ฐ์ ๊ฐ์ง๊ณ  ์ธ๊ธฐ ๊ฒ์์ด๋ฅผ ๊ตฌํํ๋ค

```python
popular_list = {}
if request.method == "GET":
    search = request.GET.get("searched", "")

	if not search.isdigit() and not search == "":
        if Review.objects.filter(
            Q(title__icontains=search)
            | Q(content__icontains=search)
            | Q(place__icontains=search)
        ):
            popular_list[search] = popular_list.get(search, 0) + 1

	for k, v in sorted(popular_list.items(), key=lambda x: -x[1]):
        if Search.objects.filter(title=k):
            s = Search.objects.get(title=k)
            s.count += 1
            s.save()
        else:
            s = Search(title=k, count=v)
            s.save()
    popular = Search.objects.order_by("-count")[:10]
```

- `if not search.isdigit() and not search == "":`
  - ์ ํ์  ์ฌํญ. ๋น์นธ์ ๊ฒ์์ด๋ผ๊ณ  ์ฐฉ๊ฐํ๊ฑฐ๋, ๊ทธ๋ฅ ๋ฒํธ๋ฅผ ๊ฒ์์ด๋ก ์ฐฉ๊ฐํ  ์ ์์ด ์ค์ ํ๋ค
- `popular_list[search] = popular_list.get(search, 0) + 1`
  - `popular_list`์ ๊ฒ์์ด `search`๋ฅผ key๋ก ์ฐพ๊ณ , ํ๋ฒ ์ฐพ์์ผ๋ 1์ ๋ํด์ค๋ค
  - `.get(key, [, value])`
    - get์ ํตํด, ๋์๋๋ฆฌ์ key๊ฐ ์์ผ๋ฉด, key๋ฅผ ๋ฃ์ด์ฃผ๊ณ  value๊ฐ์ ๋ฃ์ด์ค๋ค
  - ๐๐๐ **์ฌ๊ธฐ์๋ `popular_list`์ `search` (๊ฒ์ํ ๊ฒ์์ด)๊ฐ ์์ผ๋ฉด value์ 1์ ๋ํด์ฃผ๊ณ ,์์ผ๋ฉด ํด๋น ๊ฐ์ `search` ๊ฐ์ ๋์๋๋ฆฌ์ ๋ฃ์ด์ฃผ๊ณ  0์ผ๋ก value๋ฅผ ์ ํ ๋ค, 1์ ๋ํด์ค๋ค**
- `sorted(popular_list.items(), key=lambda x: -x[1])`
  - `popular_list` ๋์๋๋ฆฌ์ ์ ์ฅ๋ ๋ฐ์ดํฐ๋ฅผ `sorted`ํตํด ์ ๋ ฌํ๋ค
  - `.items()`๋ ๋์๋๋ฆฌ์ ์๋ key์ value๋ฅผ ๊ฐ์ ธ์จ๋ค
    - ์์) `dict_items([('A', 'Geeks'), ('B', 4), ('C', 'Geeks')])`
  - `key=lambda x: -x[1]` ์์๋ key๋ฅผ input์ผ๋ก ๊ฐ์ง๊ณ  ์ค๊ณ , key์ value (`-x[1]`)๋ฅผ ๋ด๋ฆผ์ฐจ์์ผ๋ก ์ ๋ ฌํ๋ ๊ฒ
    - ์ฌ๊ธฐ์ `-x[1]`ํ๋ ์ด์ ๋ `items()`๋ก key์ value๋ฅผ ๋ถ๋ฌ์์ ๋์ tuple ํํ๋ก ์ ๋ณด๋ฅผ ๊ฐ์ง๊ณ  ์จ๋ค
    - ์ฆ `x[0]`์ key๊ฐ ๋๋ ๊ฒ์ด๊ณ  `x[1]`์ value๊ฐ ๋๋ค

```python
for k, v in sorted(popular_list.items(), key=lambda x: -x[1]):
	if Search.objects.filter(title=k):
            s = Search.objects.get(title=k)
            s.count += 1
            s.save()
        else:
            s = Search(title=k, count=v)
            s.save()
```

- `if Search.objects.filter(title=k)`
  - ๋จ์ฝ `Search` ๋ชจ๋ธ์ title ํ๋์ `k` (key)๊ฐ ์์ผ๋ฉด 

- `s = Search.objects.get(title=k)`
  - s ์ `Search` ๋ชจ๋ธ์ ํด๋น titleํ๋์ `k` ๊ฐ๊ณผ ๊ฐ์ queryset์ ๊ฐ์ง๊ณ  ์ค๊ณ 
- `s.count += 1`
  - s์ queryset์ count ํ๋์ 1์ ๋ํด์ฃผ๊ณ 
- `s.save()`
  - ์ ์ฅ์ ํ๋ค
- ๋ง์ฝ `Search` ๋ชจ๋ธ์, ๊ฒ์ํ ๊ฒ์์ด๊ฐ ์๋ค๋ฉด
  - `s = Search(title=k, count=v)` : Search ๋ชจ๋ธ์ ๊ฒ์์ด (k)์, ๊ฒ์๋ ๊ฐ์ (v)๋ฅผ ์ ์ฅํ๋ค



#### arrange ๊ธฐ๋ฅ

```python
sort = request.GET.get("sorted", "")

if sort == "pop":
        search_list = search_list.order_by("-like_users")
        sort="pop"

if sort == "recent":
        search_list = search_list.order_by("-updated_at")
        sort="recent"
```

- `sort = request.GET.get("sorted", "")`
  - `sort`๋ผ๋ ๋ณ์๋ฅผ ๋ง๋ค๊ณ  client๊ฐ ์์ฒญํ ๋ฐ์ดํฐ๋ฅผ ํตํด, ์ ๋ ฌ์ ํ๋ค
  - ์ฌ๊ธฐ์๋ ์ธ๊ธฐ์๊ณผ ์ต์ ์, ๋ ์ค์ ํ๋์ ๋ฐ์ดํฐ๊ฐ ๋ค์ด์ฌ ์ ์๋ค
- `if sort == "pop"`
  - `sort`์ ๊ฐ์ด `pop`์ด๋ฉด ์ธ๊ธฐ์์ผ๋ก ์ ๋ ฌํ๋ค
  - ์ฌ๊ธฐ์ ์ธ๊ธฐ์์ ์ ์ ๋ค์ด ์ข์์๋ฅผ ๋๋ฅธ ์๋ฅผ ๋ด๋ฆผ์ฐจ์์ผ๋ก ์ ๋ ฌ
- `if sort == "recent"`
  - `sort`์ ๊ฐ์ด `recent`์ด๋ฉด ์ต์ ์์ผ๋ก ์ ๋ ฌ์ ํ๋ค
  - ์ฌ๊ธฐ์ ์ต์ ์์, ์ ์ ๋ค์ด ๊ธ์ ์ฌ๋ฆฌ๊ฑฐ๋ ์์ ๋ ์ต์  ์์ ๊ธฐ์ค์ผ๋ก ๋ด๋ฆผ์ฐจ์์ผ๋ก ์ ๋ ฌ

##### search.html

```html
<div class="search-cate container">
  <div class="search-cate-words">
    <a class="search-cate-word" href="?searched={{ search }}&sorted=pop"> ์ธ๊ธฐ์</a>
    <a class="search-cate-word ms-3" href="?searched={{ search }}&sorted=recent">์ต์ ์</a>
  </div>
</div>
```

- `href="?searched={{ search }}&sorted=pop`
  - ํด๋น ๊ฒ์์ด์ ๋ํ queryset๋ค์ค ์ธ๊ธฐ์์ผ๋ก ์ ๋ ฌ์ ํ๋ค
  - views.py๋ก `sorted=pop`์ ๋ณด๋ธ๋ค. ๊ทธ๋ฌ๋ฉด ์์ ์๋ ํจ์๋๋ก ์ฒ๋ฆฌ๊ฐ ๋๋ค

### โ๏ธ ๋น๋๊ธฐ

#### ๋๊ธ ๋น๋๊ธฐ

![์ธ๋ฏธํ๋ก์ ํธ_๋น๋๊ธฐ](Final_1.assets/์ธ๋ฏธํ๋ก์ ํธ_๋น๋๊ธฐ.png)

![์ธ๋ฏธํ๋ก์ ํธ_๋น๋๊ธฐ2](Final_1.assets/์ธ๋ฏธํ๋ก์ ํธ_๋น๋๊ธฐ2.png)

![์ธ๋ฏธํ๋ก์ ํธ_๋น๋๊ธฐ3](Final_1.assets/์ธ๋ฏธํ๋ก์ ํธ_๋น๋๊ธฐ3.png)



#### ๋๊ธ ์ญ์  ๋น๋๊ธฐ

![์ธ๋ฏธํ๋ก์ ํธ_๋น๋๊ธฐ4](Final_1.assets/์ธ๋ฏธํ๋ก์ ํธ_๋น๋๊ธฐ4.png)

![์ธ๋ฏธํ๋ก์ ํธ_๋น๋๊ธฐ5](Final_1.assets/์ธ๋ฏธํ๋ก์ ํธ_๋น๋๊ธฐ5-16677271832286.png)

[โซ๋๊ธ ์์ฑ ๋น๋๊ธฐ ๋ณด๋ฌ๊ฐ๊ธฐ](#๋๊ธ-๋น๋๊ธฐ)

[โซ์๋ก๊ฐ๊ธฐ](#-์ต์ข-ํ๋ก์ ํธ-1)



#### ๋๊ธ ์์  ๋น๋๊ธฐ

![์ธ๋ฏธํ๋ก์ ํธ_๋น๋๊ธฐ6](Final_1.assets/์ธ๋ฏธํ๋ก์ ํธ_๋น๋๊ธฐ6.png)

![์ธ๋ฏธํ๋ก์ ํธ_๋น๋๊ธฐ7](Final_1.assets/์ธ๋ฏธํ๋ก์ ํธ_๋น๋๊ธฐ7.png)



[โซ๋๊ธ ์์ฑ ๋น๋๊ธฐ ๋ณด๋ฌ๊ฐ๊ธฐ](#๋๊ธ-๋น๋๊ธฐ)

[โซ์๋ก๊ฐ๊ธฐ](#-์ต์ข-ํ๋ก์ ํธ-1)



## โ๏ธ ํ๋ก์ ํธ in PPT

![ppt1](Final_1.assets/ppt1.png)

![ppt2](Final_1.assets/ppt2.png)

![ppt3](Final_1.assets/ppt3.png)

![ppt4](Final_1.assets/ppt4.png)

![ppt5](Final_1.assets/ppt5.png)

![ppt6](Final_1.assets/ppt6.png)

![ppt7](Final_1.assets/ppt7.png)

![ppt8](Final_1.assets/ppt8.png)

![ppt9](Final_1.assets/ppt9.png)



[โซ์๋ก๊ฐ๊ธฐ](#-์ต์ข-ํ๋ก์ ํธ-1)