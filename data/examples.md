# (X, y) Examples for Test Case Generation

**Example 1:**
* **X (Input):** `public int add(int a, int b) { return a + b; }`
* **y (Output):** `@Test public void testAdd() { assertEquals(5, add(2, 3)); }`

**Example 2:**
* **X (Input):** `public boolean isEven(int n) { return n % 2 == 0; }`
* **y (Output):** `@Test public void testIsEven() { assertTrue(isEven(4)); assertFalse(isEven(3)); }`
