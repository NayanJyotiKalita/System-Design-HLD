# Caching Strategy

## Problem statement
In the context of system design, which of the following caching strategies is used in most relational database storage engines with write-heavy workloads?

## Options: Pick one correct answer from below

Cache-Aside

Write-Back

Read-Through Cache

Write-Through Cache

---

# Solution description
*2* --> Write back is a storage method in which data is written into the cache every time a change occurs, but is written into the corresponding location in the main memory only at specified intervals or under certain conditions. This is sometimes called write-behind as well. Write back caches improve the write performance and are good for write-heavy workloads.
