---
layout: post
title:  "---
layout: post
title:  "What is the “=~” operator in Ruby?"
date:   2016-03-20 19:05:34 +0000
categories: regex
---

=~ => Regular expression pattern match operator.

The =~ operator matches the regular expression against a string, and it returns either the offset of the match from the string if it is found, otherwise nil.

Example

```sh
>> s = 'how now brown cow'

>> s =~ /cow/
=> 14
>> s =~ /now/
=> 4
>> s =~ /cat/
=> nil
```