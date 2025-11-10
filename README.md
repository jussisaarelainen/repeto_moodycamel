moodycamel::ConcurrentQueue allocator modifications.

ConcurrentQueue now has extra template parameter: Alloc.

Alloc must provide two methods:

void* malloc(size_t)
void free(void*)

Jussi Saarelainen
Nov 2025
