# Kotlin: Unexpected List Modification with removeIf()

This example showcases a common error when using the `removeIf` function in Kotlin. The `removeIf` function modifies the list in place, rather than returning a new list. This can lead to unexpected behavior if not handled correctly.

**Problem:**
The `removeIf` function directly modifies the original list. This behavior might be unexpected for developers who expect it to return a new list.

**Solution:**
To avoid modifying the original list, use the `filter` function to create a new list containing only the elements that satisfy the condition.