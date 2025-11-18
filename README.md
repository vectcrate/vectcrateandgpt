 (cd "$(git rev-parse --show-toplevel)" && git apply --3way <<'EOF' 
diff --git a/README.md b/README.md
new file mode 100644
index 0000000000000000000000000000000000000000..b568e2041dc2deeaa6ae2067599c896e0a5e9f40
--- /dev/null
+++ b/README.md
@@ -0,0 +1,10 @@
+# vectcrateandgpt
+
+এই রেপোজিটরিতে একটি সাদাসিধে ডেমো রয়েছে।
+
+## Demo Steps
+নিচের ধাপগুলো অনুসরণ করে ডেমো চালাতে পারেন:
+
+1. রেপোজিটরিটি ক্লোন বা ডাউনলোড করে `vectcrateandgpt` ফোল্ডারে যান।
+2. ফোল্ডারে গিয়ে `python -m http.server 8000` চালিয়ে একটি স্থানীয় সার্ভার শুরু করুন।
+3. ব্রাউজারে `http://localhost:8000/index.html` খুলে ডেমোটি দেখুন।
 
EOF
)
