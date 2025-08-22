# I will be noting down things I learn during the duration of this project.

1. @Controller is used for returning pages/ views and @RestController is used for returning JSON/ text APIs.
2. @RestController -> @Controller + @ResponseBody
3. For giving dynamic data
 ```java
       @GetMapping("/")
        public String home(Model model){ // Model model is used to give dynamic data
        model.addAttribute("title", "URL Shortener - Tharun");
        return "index";
   ```
