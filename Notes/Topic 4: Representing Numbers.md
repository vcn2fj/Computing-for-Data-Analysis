* How to store a number on computer?

<img width="479" height="271" alt="image" src="https://github.com/user-attachments/assets/0f3b6fe7-4186-4fbc-a0e2-3fc08969907c" />

* Value of string is sum of digits: 7+80+800+9000...
* Changing the base from base 10 to base 2
  - "bit" stands for binary digits

<img width="460" height="208" alt="image" src="https://github.com/user-attachments/assets/8e71c7c4-dad9-452c-baa1-49ce7e5281dd" />

* Fractional values: includes negative positions

<img width="236" height="204" alt="image" src="https://github.com/user-attachments/assets/6093adc9-101a-4f93-ae8e-c8ac9f29fa44" />

* Base doesn't actually matter

<img width="449" height="110" alt="image" src="https://github.com/user-attachments/assets/8e50bc80-437d-4997-8064-efb3092be677" />

* infinite base 2 - shows that most computers only store approximations
  
<img width="528" height="114" alt="image" src="https://github.com/user-attachments/assets/db6a3d60-c0c4-43c8-b8af-86f14412b449" />

* to encode numbers with fractional parts, fixed sized encoding can be represented by a tuple

<img width="514" height="275" alt="image" src="https://github.com/user-attachments/assets/0a020b48-c415-4691-857c-207b0b615a43" />

<img width="468" height="228" alt="image" src="https://github.com/user-attachments/assets/72c5ba1f-6ada-4ae6-825a-9e17b59b1308" />

<img width="454" height="235" alt="image" src="https://github.com/user-attachments/assets/3d3b5b4b-9cf7-456a-9201-4b73cd6385e8" />

* Rounding errors

<img width="494" height="266" alt="image" src="https://github.com/user-attachments/assets/72bf4a29-bb50-4fa2-bfc6-0678746aea9c" />

<img width="524" height="215" alt="image" src="https://github.com/user-attachments/assets/21b894b8-301e-46f0-be97-f5b79bcbe3a1" />

* In one case with inexact inputs, the two programs produced exactly the same results, yet with exactly represented inputs the two programs produced different results.

* IEEE 754
  - In binary that number before the decimal can only be the value one unless the whole number is zero. Therefore, it does not need to be stored if its always equal to one
  - The exponent range will be slightly asymmetric so that format can encode special values like infinity or NaN
  - IEEE 754 defines some standard sizes which we can then rely on being available on any compliant hardware.
  - Relative error is at most machine epsilon (value that depends on the floating point format, and
it bounds the largest relative error due to round-off)
 
<img width="449" height="230" alt="image" src="https://github.com/user-attachments/assets/a4130cba-68ea-4508-941f-ba660b5fe1d9" />

<img width="497" height="290" alt="image" src="https://github.com/user-attachments/assets/37c23291-7715-44f5-baaf-30fd58981c3b" />

<img width="441" height="175" alt="image" src="https://github.com/user-attachments/assets/a09077f6-a3e4-4b52-b4d1-a23ce2e59258" />

* IEEE double-precision:

<img width="488" height="250" alt="image" src="https://github.com/user-attachments/assets/2454767f-6616-42c0-a519-4e60339f9adc" />

* High level analytical framework for analyzing errors:

<img width="443" height="251" alt="image" src="https://github.com/user-attachments/assets/c07c4bcf-30dd-4d09-8c00-8d11cef4b827" />

* The absolute difference is known as the forward error. If you can successfully calculate upper bound on forward error then you've done a forward stability analysis.
  - Can claim that your algorithm or program is forward stable if forward error is small
 
* Backwards stability analysis

<img width="456" height="265" alt="image" src="https://github.com/user-attachments/assets/e23aa189-b4dc-4d70-be70-dcccd7592e3f" />

<img width="523" height="236" alt="image" src="https://github.com/user-attachments/assets/88a006cf-9e80-4942-b454-4b8631e37ebd" />

<img width="454" height="281" alt="image" src="https://github.com/user-attachments/assets/068e4b37-7579-456e-809c-779bec8a6321" />

* Computer produces rounded and truncated version of fl(a+b) for some operation (a+b)
  - Delta is relative error
  - abs(delta) <= machine epsilon (worst case value)
 
<img width="391" height="124" alt="image" src="https://github.com/user-attachments/assets/c2764704-95b2-4df5-ac94-d80a6f15b807" />

* Problem of summing a list of numbers
  - Pt. 1 ignore the possibility of floating pt rounding errors
 
<img width="531" height="276" alt="image" src="https://github.com/user-attachments/assets/0d52eba7-f38a-4b33-8175-b26779b3376b" />

* Now with floating pt rounding errors:

<img width="506" height="292" alt="image" src="https://github.com/user-attachments/assets/bc032346-ea86-45e5-8e6f-1f8bfe3e3c7c" />

<img width="544" height="277" alt="image" src="https://github.com/user-attachments/assets/34ed63dc-ed50-4a8c-939b-6f4f665305fc" />

<img width="524" height="272" alt="image" src="https://github.com/user-attachments/assets/676e2970-30b6-4d80-9fb2-a1a63495bbec" />
