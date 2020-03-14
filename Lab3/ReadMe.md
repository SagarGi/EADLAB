# **Lab 3**
# **Date : 14th march 2020**
# **Objective 1: Servlet Interface**

# **Theory :**

Servlet Interface, When the Servlet is deployed in the server the Servlet container creates life cycle of the Servlet.
The central abstraction in the Servlet API is the Servlet interface, all the Servlets have to implement this interface 
either directly or by extending a class such as GenericServlet, HttpServlet. Following are the different methods of servlet interface.
1. public void init(ServletConfig config)
2. public void service(ServletRequest request,ServletResponse response)
3. public void destroy()
4. public ServletConfig getServletConfig()
5. public String getServletInfo()

# **Objective 2: Java Servlet POST Example*

# **Theory :**

A generally more reliable method of passing information to a backend program is the POST method. This packages the information in exactly the same way as GET method, but instead of sending it as a text string after a ? (question mark) in the URL it sends it as a separate message. This message comes to the backend program in the form of the standard input which you can parse and use for your processing. Servlet handles this type of requests using doPost() method.

Reading Form Data using Servlet

Servlets handles form data parsing automatically using the following methods depending on the situation −
- getParameter() − You call request.getParameter() method to get the value of a form parameter.
- getParameterValues() − Call this method if the parameter appears more than once and returns multiple values, for example checkbox.
- getParameterNames() − Call this method if you want a complete list of all parameters in the current request.






