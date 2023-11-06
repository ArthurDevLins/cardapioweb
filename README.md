# Formulario JSP para coletar dados do usuario 
<%@ page language="java" contentType="text/html; charset=UTF-8" pageEncoding="UTF-8"%>
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Atualizar Senha</title>
</head>
<body>
    <form action="UpdatePasswordServlet" method="post">
        <label for="username">Usuário:</label>
        <input type="text" name="username" required><br>
        
        <label for="password">Nova Senha:</label>
        <input type="password" name="password" required><br>
        
        <input type="submit" value="Atualizar Senha">
    </form>
</body>
</html>
