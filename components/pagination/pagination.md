Pagination
==========

Moving between pages has become less common with the advent of longer pages and AJAX loading, but it can still be useful for long, repetitive listings or content.

```ahcx
<foundation.Pagination leftUnavailable="true">
  <foundation.PaginationItem url="#1" name="1" current="true" />
  <foundation.PaginationItem url="#2" name="2" />
  <foundation.PaginationItem url="#3" name="3" />
  <foundation.PaginationItem url="#4" name="4" />
  <foundation.PaginationItem name="…" unavailable="true" />
  <foundation.PaginationItem url="#12" name="12" />
  <foundation.PaginationItem url="#13" name="13" />
</foundation.Pagination>
```
