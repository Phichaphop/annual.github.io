<!DOCTYPE html>
<html lang="th">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HRIS Annual Leave Hub - แผนพักร้อน</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        'primary': '#059669', // สีเขียวมรกต (Emerald) ดูผ่อนคลายและ Pro
                        'secondary': '#34D399', // เขียวอ่อน
                        'bg-light': '#F0FFF4', // พื้นหลังเขียวอ่อนมาก
                        'card-bg': '#FFFFFF',
                    }
                }
            }
        }
    </script>
</head>
<body class="bg-bg-light min-h-screen flex justify-center items-start pt-10 pb-10 font-sans">

    <div class="container w-full max-w-xl mx-auto p-6 md:p-10 bg-card-bg rounded-2xl shadow-2xl transition-all duration-300">
        <header class="text-center mb-10">
            <h1 class="text-3xl md:text-4xl font-extrabold text-primary mb-1 tracking-tight">
                <span class="mr-2">🌴</span> Annual Leave Hub
            </h1>
            <p class="text-base md:text-lg text-gray-500 font-medium italic">HRIS System Hub for Trax Intertrade Co., Ltd.</p>
        </header>

        <div class="space-y-5 mb-8">
            <a href="https://www.appsheet.com/start/a49f2634-aa91-4c4e-9f27-1c254155de95" target="_blank" 
               class="link-button block w-full py-5 px-6 bg-primary text-white font-black text-xl rounded-xl shadow-xl hover:bg-green-700 transition duration-300 ease-in-out transform hover:scale-[1.01]">
                <span class="mr-2">📲</span> App Sheet: วางแผนพักร้อน (Click Here!)
            </a>
            
            <a href="https://script.google.com/macros/s/AKfycbzzvagHEtWsLdwUoSqzdaAZ1bRydn-HwUZvwaRKMPGWk4NCKfcowB3k0E0JauShx1AtOg/exec" target="_blank" 
               class="link-button block w-full py-4 px-6 border-2 border-primary text-primary font-bold rounded-xl shadow-md hover:bg-primary hover:text-white transition duration-300 ease-in-out transform hover:scale-[1.01]">
                <span class="mr-2">🖨️</span> App Script: ปริ้นแบบฟอร์มลาพักร้อน
            </a>
        </div>

        <section class="space-y-4">
            
            <div class="dropdown-link bg-gray-50 rounded-xl shadow-lg border border-gray-200 overflow-hidden">
                <a href="https://www.canva.com/design/DAG10gZ_EbM/2Y4L11rum5ByYrfE9GUHYQ/edit?utm_content=DAG10gZ_EbM&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton" target="_blank" 
                   class="link-button block w-full py-4 px-6 bg-gray-200 text-gray-800 font-semibold text-lg rounded-xl hover:bg-gray-300 transition duration-300 ease-in-out">
                    <span class="mr-3 text-xl">📘</span> Manual: คู่มือวิธีการใช้ระบบ
                </a>
            </div>

            <div class="dropdown-link bg-gray-50 rounded-xl shadow-lg border border-gray-200 overflow-hidden">
                <button class="dropdown-toggle w-full flex items-center justify-between p-4 bg-gray-200 text-gray-800 font-semibold text-lg hover:bg-gray-300 transition duration-300 ease-in-out" data-target="contact-info">
                    <div class="flex items-center">
                        <span class="mr-3 text-xl">🙋</span> ติดต่อผู้ดูแลระบบ (HRIS: น้องปัง)
                    </div>
                    <span class="toggle-icon transform transition-transform duration-300">▼</span>
                </button>
                <div id="contact-info" class="dropdown-content hidden text-center">
                    
                    <p class="pt-4 pb-2 px-6 text-base font-semibold text-gray-700">
                        ✨ Quick Connect: สแกน QR Code ไลน์ได้เลย! 👇
                    </p>

                    <div class="p-4">
                        <img 
                            src="Link QR 90681322.jpg"
                            alt="Line QR Code for Pung" 
                            class="mx-auto w-40 h-40 object-contain rounded-lg border-2 border-primary/50 shadow-lg"
                        >
                    </div>

                    <p class="py-2 px-6 text-base font-medium text-gray-500">
                        หรือช่องทางอื่นๆ:
                    </p>
                    <a href="mailto:phichaphop.boo@libgroup.co.th" class="sub-link block py-2 px-6 text-primary hover:bg-secondary/10 transition duration-200 border-t border-gray-100">
                        📧 phichaphop.boo@libgroup.co.th
                    </a>
                    <a href="line://ti/p/~phichaphobboonthon" class="sub-link block py-2 px-6 text-primary hover:bg-secondary/10 transition duration-200 border-t border-gray-100">
                        💬 Line ID: phichaphobboonthon
                    </a>
                </div>
            </div>

        </section>
        
        <footer class="text-center mt-10 text-gray-400 text-sm">
            <p>&copy; 2025 HRIS Pung | <span class="text-primary font-semibold">Trax Intertrade Co., Ltd.</span></p>
        </footer>
    </div>

    <script>
        document.addEventListener('DOMContentLoaded', function() {
            const dropdownToggles = document.querySelectorAll('.dropdown-toggle');

            dropdownToggles.forEach(toggle => {
                toggle.addEventListener('click', function() {
                    const targetId = this.getAttribute('data-target');
                    const content = document.getElementById(targetId);
                    const icon = this.querySelector('.toggle-icon'); 

                    if (content.classList.contains('hidden')) {
                        content.classList.remove('hidden');
                        icon.classList.add('rotate-180'); 
                    } else {
                        content.classList.add('hidden');
                        icon.classList.remove('rotate-180');
                    }
                });
            });
        });
    </script>
</body>
</html>
