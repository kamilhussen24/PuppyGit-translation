# PuppyGit-অনুবাদ

## PuppyGit বাংলা অনুবাদ  
**PuppyGit** প্রোগ্রামের বাংলা ভাষায় অনুবাদ

**PuppyGit** হলো [Git](https://git-scm.com/) রিপোজিটরি (লোকাল এবং রিমোট) নিয়ে কাজ করার জন্য একটি [Android](https://bn.wikipedia.org/wiki/%E0%A6%85%E0%A7%8D%E0%A6%AF%E0%A6%BE%E0%A6%A8%E0%A7%8D%E0%A6%A1%E0%A7%8D%E0%A6%B0%E0%A7%9F%E0%A6%A1) অ্যাপ্লিকেশন।

- [প্রোগ্রামের রিপোজিটরি এবং বাংলা অনুবাদ সহ সর্বশেষ সংস্করণ](https://github.com/catpuppyapp/PuppyGit)  
- [মূল ইংরেজি ফাইল](https://github.com/catpuppyapp/PuppyGit/blob/main/app/src/main/res/values/strings.xml)  
- [PuppyGit রিপোজিটরিতে বাংলা অনুবাদ ফাইল](https://github.com/catpuppyapp/PuppyGit/blame/main/app/src/main/res/values-bn/strings.xml)  

***যদি আপনি বাংলা অনুবাদে কোনো ভুল বা অসঙ্গতি খুঁজে পান, দয়া করে আমাদের জানান।***  
আপনি চাইলে আমাদের সাথে অনুবাদক হিসেবে যোগ দিতে পারেন। এর জন্য [এই রিপোজিটরিতে একটি Issue (আবেদন) তৈরি করুন](https://github.com/triksterr/PuppyGit-translation/issues)।  

**PuppyGit** বাংলা ভাষায় আরামদায়ক এবং সুন্দরভাবে ব্যবহার করার জন্য শুভকামনা!

## PuppyGit-এর জন্য অনুবাদ নির্দেশিকা
1. **strings.xml ফাইল ডাউনলোড করুন**: [strings.xml](https://github.com/catpuppyapp/PuppyGit/blob/main/app/src/main/res/values/strings.xml) ফাইলটি ডাউনলোড করুন।  
2. **মানগুলো বাংলায় অনুবাদ করুন**: ফাইলের মধ্যে থাকা ইংরেজি স্ট্রিংগুলো বাংলায় অনুবাদ করুন। উদাহরণস্বরূপ:  
   `<string name="help">help translate</string>` → `<string name="help">অনুবাদে সাহায্য</string>`  
3. **আবেদন জমা দিন**: [মূল রিপোজিটরিতে](https://github.com/catpuppyapp/PuppyGit) একটি Issue (আবেদন) তৈরি করুন এবং অনুবাদকৃত ফাইলটি সংযুক্ত করুন। আবেদনে উল্লেখ করুন যে এটি বাংলা ভাষার অনুবাদ।  
4. **বিশেষ নোট**:  
   strings.xml ফাইলে `"ph_a3f241dc_NUMBER"` ধরনের স্ট্রিংগুলো হলো প্লেসহোল্ডার ভেরিয়েবল। এই স্ট্রিংগুলোর শেষে থাকা সংখ্যা (যেমন `_1`, `_2`) ভেরিয়েবলের অবস্থান নির্দেশ করে।  
   **উদাহরণ**:  
   `<string name="str1">name: ph_a3f241dc_1, age: ph_a3f241dc_2</string>`  
   প্রোগ্রাম চলাকালীন এটি এমনভাবে প্রতিস্থাপিত হয় যে প্লেসহোল্ডারের জায়গায় প্রকৃত মান বসে, যেমন:  
   **`"name: abc, age: 123"`**।  

   যদি আপনি ভুলবশত প্লেসহোল্ডারের সংখ্যার ক্রম পরিবর্তন করেন, যেমন:  
   `<string name="str1">name: ph_a3f241dc_2, age: ph_a3f241dc_1</string>`  
   তাহলে অ্যাপ্লিকেশনে টেক্সট ভুলভাবে প্রদর্শিত হতে পারে, যেমন:  
   **`"name: 123, age: abc"`**।  

   **তাই অনুবাদের সময় প্লেসহোল্ডারগুলোর ক্রম এবং গঠন অপরিবর্তিত রাখুন।**