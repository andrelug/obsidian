<%* if (tp.file.title.charAt(0) == "{" ) { %>
<%~tp.file.include("[[Book]]")%>
<%* } else if (tp.file.title.charAt(0) == "@" ) { %>
<%~tp.file.include("[[People]]")%>
<%* } else if (tp.file.title.charAt(0) == "!" ) { %>
<%~tp.file.include("[[Tweet]]")%>
<%* } else if (tp.file.title.charAt(0) == "%" ) { %>
<%~tp.file.include("[[Podcast]]")%>
<%* } else if (tp.file.title.charAt(0) == "+" ) { %>
<%~tp.file.include("[[Video]]")%>
<%* } else if (tp.file.title.charAt(0) == "=" ) { %>
<%~tp.file.include("[[Thought]]")%>
<%* } else if (tp.file.title.charAt(0) == "&" ) { %>
<%~tp.file.include("[[People]]")%>
<%* } _%>