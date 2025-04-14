<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <title>Olá Momo</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <h1>Olá Momo</h1>
    <div class="gallery">
        <div class="wallpaper" onclick="openModal('modal1')">
            <img src="wallpapers/img 1.jpg" alt="Wallpaper 1">
        </div>
        <div class="wallpaper" onclick="openModal('modal2')">
            <img src="wallpapers/img 2.jpg" alt="Wallpaper 2">
        </div>
        <div class="wallpaper" onclick="openModal('modal3')">
            <img src="wallpapers/img 3.jpg" alt="Wallpaper 3">
        </div>
    </div>

    <!-- Modals -->
    <div id="modal1" class="modal">
        <div class="modal-content">
            <span class="close" onclick="closeModal('modal1')">&times;</span>
            <p>Hey, só queria te dizer que você é a pessoa mais especial que apareceu na minha vida</p>
        </div>
    </div>
    <div id="modal2" class="modal">
        <div class="modal-content">
            <span class="close" onclick="closeModal('modal2')">&times;</span>
            <p>Você eh meu maior presente e minha melhor escolha na vida</p>
        </div>
    </div>
    <div id="modal3" class="modal">
        <div class="modal-content">
            <span class="close" onclick="closeModal('modal3')">&times;</span>
            <p>E não quero jamais ficar sem você. Eu te amo meu amor, muitooooooooooo</p>
        </div>
    </div>

    <script>
        function openModal(modalId) {
            document.getElementById(modalId).style.display = 'flex';
        }

        function closeModal(modalId) {
            document.getElementById(modalId).style.display = 'none';
        }
    </script>
</body>
</html>
