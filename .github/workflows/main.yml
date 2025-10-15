<!DOCTYPE html>
<html lang="th">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>เกมส์ออนไลน์ - สนุกไปกับเกมที่หลากหลาย</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        body {
            box-sizing: border-box;
        }
        
        .game-card {
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        
        .game-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 20px 40px rgba(0,0,0,0.1);
        }
        
        .hero-bg {
            background: linear-gradient(rgba(0,0,0,0.4), rgba(0,0,0,0.4)), url('https://www.kaohoon.com/wp-content/uploads/2024/10/KTB-SCB-BBL-KBANK-BAY_2024-10-01_up.jpg');
            background-size: cover;
            background-position: center 30%;
            background-repeat: no-repeat;
        }
        
        .pulse-animation {
            animation: pulse 2s infinite;
        }
        
        @keyframes pulse {
            0%, 100% { opacity: 1; }
            50% { opacity: 0.7; }
        }
        
        .game-icon {
            width: 60px;
            height: 60px;
            margin: 0 auto 1rem;
        }
        
        .nav-link:hover {
            color: #667eea;
            transition: color 0.3s ease;
        }
    </style>
</head>
<body class="bg-gradient-to-br from-blue-50 via-purple-50 to-pink-50 font-sans">
    <!-- Navigation -->
    <nav class="bg-white shadow-lg sticky top-0 z-50">
        <div class="max-w-7xl mx-auto px-4">
            <div class="flex justify-between items-center h-16">
                <div class="flex items-center">
                    <div class="text-2xl font-bold text-purple-600">🎮 GameHub</div>
                </div>
                <div class="hidden md:flex space-x-8">
                    <a href="#home" class="nav-link text-gray-700 hover:text-purple-600 font-medium">หน้าแรก</a>
                    <a href="#games" class="nav-link text-gray-700 hover:text-purple-600 font-medium">เกมส์</a>
                    <a href="#leaderboard" class="nav-link text-gray-700 hover:text-purple-600 font-medium">สถิติ</a>
                    <a href="#about" class="nav-link text-gray-700 hover:text-purple-600 font-medium">เกี่ยวกับ</a>
                </div>
                <button class="bg-purple-600 text-white px-6 py-2 rounded-full hover:bg-purple-700 transition duration-300">
                    เข้าสู่ระบบ
                </button>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="hero-bg text-white py-20">
        <div class="max-w-7xl mx-auto px-4 text-center">
            <h1 class="text-5xl md:text-6xl font-bold mb-6">
                สนุกไปกับเกมส์ออนไลน์
            </h1>
            <p class="text-xl md:text-2xl mb-8 opacity-90">
                เล่นเกมส์ฟรี ไม่ต้องดาวน์โหลด พร้อมระบบคะแนนและการแข่งขัน
            </p>
            <button onclick="scrollToGames()" class="bg-white text-purple-600 px-8 py-4 rounded-full text-lg font-semibold hover:bg-gray-100 transition duration-300 pulse-animation">
                เริ่มเล่นเลย! 🚀
            </button>
        </div>
    </section>

    <!-- Games Section -->
    <section id="games" class="py-20 relative" style="background: linear-gradient(rgba(0,0,0,0.7), rgba(0,0,0,0.7)), url('https://www.jdbti.org/wp-content/uploads/2024/11/Online-casino-casino-online-poker-poker-Dice-chips-tokens-roulette-online-gambling-azart-games-Facility-for-certain-types-of-gambling-Betting-money-on-games-Generative-AI.jpeg'); background-size: cover; background-position: center; background-repeat: no-repeat;">
        <div class="max-w-7xl mx-auto px-4">
            <h2 class="text-4xl font-bold text-center text-white mb-4">เกมส์ยอดนิยม</h2>
            <p class="text-center text-gray-200 mb-12">เลือกเล่นเกมส์ที่คุณชอบ</p>
            
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 xl:grid-cols-4 gap-8">
                <!-- Snake Game -->
                <div class="game-card bg-white rounded-xl shadow-lg p-6 border border-gray-100 relative overflow-hidden">
                    <div class="absolute inset-0 bg-cover bg-center opacity-60" style="background-image: url('https://matrix-info.com/wp-content/uploads/2024/04/image-67-1024x1024-1.png');"></div>
                    <div class="relative z-10">
                        <div class="game-icon text-center mb-4">
                            <div class="text-4xl opacity-0">🐍</div>
                        </div>
                        <h3 class="text-xl font-bold text-gray-800 mb-2 text-center">เกมงู</h3>
                        <p class="text-gray-600 text-center mb-4">เกมคลาสสิกที่ทุกคนรู้จัก ควบคุมงูให้กินอาหารและเติบโต</p>
                        <div class="text-center">
                            <button onclick="playSnakeGame()" class="bg-green-500 text-white px-6 py-2 rounded-full hover:bg-green-600 transition duration-300">
                                เล่นเลย
                            </button>
                        </div>
                    </div>
                </div>

                <!-- Memory Game -->
                <div class="game-card bg-white rounded-xl shadow-lg p-6 border border-gray-100 relative overflow-hidden">
                    <div class="absolute inset-0 bg-cover bg-center opacity-60" style="background-image: url('https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRVD-mAStUufV_ZOMVRV_91Z6G1Euaa4cr_9Q&s'); background-position: center 30%;"></div>
                    <div class="relative z-10">
                        <div class="game-icon text-center mb-4">
                            <div class="text-4xl opacity-0">🧠</div>
                        </div>
                        <h3 class="text-xl font-bold text-gray-800 mb-2 text-center">เกมจำ</h3>
                        <p class="text-gray-600 text-center mb-4">ทดสอบความจำของคุณ จับคู่การ์ดให้ถูกต้อง</p>
                        <div class="text-center">
                            <button onclick="playMemoryGame()" class="bg-blue-500 text-white px-6 py-2 rounded-full hover:bg-blue-600 transition duration-300">
                                เล่นเลย
                            </button>
                        </div>
                    </div>
                </div>

                <!-- Quiz Game -->
                <div class="game-card bg-white rounded-xl shadow-lg p-6 border border-gray-100 relative overflow-hidden">
                    <div class="absolute inset-0 bg-cover bg-center opacity-60" style="background-image: url('https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQPdykygMneLovIyhT3RfJMlNi_EMKjYSWAmw&s');"></div>
                    <div class="relative z-10">
                        <div class="game-icon text-center mb-4">
                            <div class="text-4xl opacity-0">❓</div>
                        </div>
                        <h3 class="text-xl font-bold text-gray-800 mb-2 text-center">เกมตอบคำถาม</h3>
                        <p class="text-gray-600 text-center mb-4">ทดสอบความรู้ทั่วไป ตอบคำถามให้ถูกต้อง</p>
                        <div class="text-center">
                            <button onclick="playQuizGame()" class="bg-purple-500 text-white px-6 py-2 rounded-full hover:bg-purple-600 transition duration-300">
                                เล่นเลย
                            </button>
                        </div>
                    </div>
                </div>

                <!-- Puzzle Game -->
                <div class="game-card bg-white rounded-xl shadow-lg p-6 border border-gray-100 relative overflow-hidden">
                    <div class="absolute inset-0 bg-cover bg-center opacity-60" style="background-image: url('https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTYrI2haA0KueB1rwL9G-yW73HuouS_13tKAw&s');"></div>
                    <div class="relative z-10">
                        <div class="game-icon text-center mb-4">
                            <div class="text-4xl opacity-0">🧩</div>
                        </div>
                        <h3 class="text-xl font-bold text-gray-800 mb-2 text-center">เกมจิ๊กซอว์</h3>
                        <p class="text-gray-600 text-center mb-4">เรียงชิ้นส่วนให้เป็นรูปภาพที่สมบูรณ์</p>
                        <div class="text-center">
                            <button onclick="playPuzzleGame()" class="bg-orange-500 text-white px-6 py-2 rounded-full hover:bg-orange-600 transition duration-300">
                                เล่นเลย
                            </button>
                        </div>
                    </div>
                </div>

                <!-- Racing Game -->
                <div class="game-card bg-white rounded-xl shadow-lg p-6 border border-gray-100 relative overflow-hidden">
                    <div class="absolute inset-0 bg-cover bg-center opacity-60" style="background-image: url('https://img5.pic.in.th/file/secure-sv1/photo_2025-03-21_23-31-50.jpg'); background-position: center 20%;"></div>
                    <div class="relative z-10">
                        <div class="game-icon text-center mb-4">
                            <div class="text-4xl opacity-0">🏎️</div>
                        </div>
                        <h3 class="text-xl font-bold text-gray-800 mb-2 text-center">เกมแข่งรถ</h3>
                        <p class="text-gray-600 text-center mb-4">ขับรถหลบหลีกสิ่งกีดขวาง ไปให้ไกลที่สุด</p>
                        <div class="text-center">
                            <button onclick="playRacingGame()" class="bg-red-500 text-white px-6 py-2 rounded-full hover:bg-red-600 transition duration-300">
                                เล่นเลย
                            </button>
                        </div>
                    </div>
                </div>

                <!-- Math Game -->
                <div class="game-card bg-white rounded-xl shadow-lg p-6 border border-gray-100 relative overflow-hidden">
                    <div class="absolute inset-0 bg-cover bg-center opacity-60" style="background-image: url('https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSmr3N-lAhvndvCdsEDjheixPWl17PR2ZgCrw&s');"></div>
                    <div class="relative z-10">
                        <div class="game-icon text-center mb-4">
                            <div class="text-4xl opacity-0">🔢</div>
                        </div>
                        <h3 class="text-xl font-bold text-gray-800 mb-2 text-center">เกมคณิตศาสตร์</h3>
                        <p class="text-gray-600 text-center mb-4">ฝึกสมองด้วยการคำนวณ แก้โจทย์ให้เร็วที่สุด</p>
                        <div class="text-center">
                            <button onclick="playMathGame()" class="bg-indigo-500 text-white px-6 py-2 rounded-full hover:bg-indigo-600 transition duration-300">
                                เล่นเลย
                            </button>
                        </div>
                    </div>
                </div>

                <!-- Adventure Game -->
                <div class="game-card bg-white rounded-xl shadow-lg p-6 border border-gray-100 relative overflow-hidden">
                    <div class="absolute inset-0 bg-cover bg-center opacity-60" style="background-image: url('https://image.winudf.com/v2/image1/Y29tLmhhbmRtb2JpLmZpc2hpbmdtYXN0ZXJfc2NyZWVuXzBfMTYyNTYwMDM3MV8wMjE/screen-0.jpg?fakeurl=1&type=.jpg');"></div>
                    <div class="relative z-10">
                        <div class="game-icon text-center mb-4">
                            <div class="text-4xl opacity-0">🗺️</div>
                        </div>
                        <h3 class="text-xl font-bold text-gray-800 mb-2 text-center">เกมผจญภัย</h3>
                        <p class="text-gray-600 text-center mb-4">สำรวจโลกใหม่ เก็บของมีค่า และเอาชนะศัตรู</p>
                        <div class="text-center">
                            <button onclick="playAdventureGame()" class="bg-emerald-500 text-white px-6 py-2 rounded-full hover:bg-emerald-600 transition duration-300">
                                เล่นเลย
                            </button>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Statistics Section -->
    <section id="leaderboard" class="py-20 bg-gray-50">
        <div class="max-w-7xl mx-auto px-4">
            <h2 class="text-4xl font-bold text-center text-gray-800 mb-12">สถิติผู้เล่น</h2>
            
            <!-- Online Stats -->
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8 mb-12">
                <div class="bg-white rounded-xl shadow-lg p-6 text-center">
                    <div class="text-4xl mb-4">🟢</div>
                    <h3 class="text-2xl font-bold text-green-600 mb-2" id="onlineCount">1,247</h3>
                    <p class="text-gray-600">ผู้เล่นออนไลน์อยู่</p>
                </div>
                
                <div class="bg-white rounded-xl shadow-lg p-6 text-center">
                    <div class="text-4xl mb-4">👥</div>
                    <h3 class="text-2xl font-bold text-blue-600 mb-2">25,891</h3>
                    <p class="text-gray-600">จำนวนผู้เล่นทั้งหมด</p>
                </div>
                
                <div class="bg-white rounded-xl shadow-lg p-6 text-center">
                    <div class="text-4xl mb-4">🎮</div>
                    <h3 class="text-2xl font-bold text-purple-600 mb-2">156,432</h3>
                    <p class="text-gray-600">เกมที่เล่นทั้งหมด</p>
                </div>
            </div>
            
            <!-- Popular Games Ranking -->
            <div class="bg-white rounded-xl shadow-lg overflow-hidden">
                <div class="bg-gradient-to-r from-purple-600 to-blue-600 text-white p-6">
                    <h3 class="text-2xl font-bold text-center">🏆 อันดับเกมที่ผู้คนเข้าเล่นมากที่สุด</h3>
                </div>
                <div class="p-6">
                    <div class="space-y-4">
                        <div class="flex items-center justify-between p-4 bg-yellow-50 rounded-lg border-l-4 border-yellow-400">
                            <div class="flex items-center">
                                <span class="text-2xl mr-4">🥇</span>
                                <div>
                                    <div class="font-bold text-gray-800">เกมงู</div>
                                    <div class="text-sm text-gray-600">เกมคลาสสิกยอดนิยม</div>
                                </div>
                            </div>
                            <div class="text-xl font-bold text-yellow-600">8,542 ครั้ง</div>
                        </div>
                        
                        <div class="flex items-center justify-between p-4 bg-gray-50 rounded-lg border-l-4 border-gray-400">
                            <div class="flex items-center">
                                <span class="text-2xl mr-4">🥈</span>
                                <div>
                                    <div class="font-bold text-gray-800">เกมจำ</div>
                                    <div class="text-sm text-gray-600">ทดสอบความจำ</div>
                                </div>
                            </div>
                            <div class="text-xl font-bold text-gray-600">6,891 ครั้ง</div>
                        </div>
                        
                        <div class="flex items-center justify-between p-4 bg-orange-50 rounded-lg border-l-4 border-orange-400">
                            <div class="flex items-center">
                                <span class="text-2xl mr-4">🥉</span>
                                <div>
                                    <div class="font-bold text-gray-800">เกมตอบคำถาม</div>
                                    <div class="text-sm text-gray-600">ทดสอบความรู้</div>
                                </div>
                            </div>
                            <div class="text-xl font-bold text-orange-600">5,234 ครั้ง</div>
                        </div>
                        
                        <div class="flex items-center justify-between p-4 bg-blue-50 rounded-lg border-l-4 border-blue-400">
                            <div class="flex items-center">
                                <span class="text-xl mr-4">4️⃣</span>
                                <div>
                                    <div class="font-bold text-gray-800">เกมผจญภัย</div>
                                    <div class="text-sm text-gray-600">สำรวจโลกใหม่</div>
                                </div>
                            </div>
                            <div class="text-xl font-bold text-blue-600">4,567 ครั้ง</div>
                        </div>
                        
                        <div class="flex items-center justify-between p-4 bg-green-50 rounded-lg border-l-4 border-green-400">
                            <div class="flex items-center">
                                <span class="text-xl mr-4">5️⃣</span>
                                <div>
                                    <div class="font-bold text-gray-800">เกมแข่งรถ</div>
                                    <div class="text-sm text-gray-600">ความเร็วและความตื่นเต้น</div>
                                </div>
                            </div>
                            <div class="text-xl font-bold text-green-600">3,892 ครั้ง</div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-20 bg-white">
        <div class="max-w-7xl mx-auto px-4">
            <div class="text-center mb-12">
                <h2 class="text-4xl font-bold text-gray-800 mb-4">เกี่ยวกับเรา</h2>
                <p class="text-xl text-gray-600">แพลตฟอร์มเกมส์ออนไลน์ที่ดีที่สุด</p>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <div class="text-center">
                    <div class="text-5xl mb-4">🎯</div>
                    <h3 class="text-xl font-bold text-gray-800 mb-2">เล่นง่าย</h3>
                    <p class="text-gray-600">ไม่ต้องดาวน์โหลด เล่นได้ทันทีบนเว็บเบราว์เซอร์</p>
                </div>
                
                <div class="text-center">
                    <div class="text-5xl mb-4">🏆</div>
                    <h3 class="text-xl font-bold text-gray-800 mb-2">แข่งขันได้</h3>
                    <p class="text-gray-600">ระบบคะแนนและอันดับ แข่งขันกับเพื่อนๆ</p>
                </div>
                
                <div class="text-center">
                    <div class="text-5xl mb-4">🆓</div>
                    <h3 class="text-xl font-bold text-gray-800 mb-2">ฟรี 100%</h3>
                    <p class="text-gray-600">เล่นได้ทุกเกมส์ฟรี ไม่มีค่าใช้จ่าย</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-800 text-white py-12">
        <div class="max-w-7xl mx-auto px-4">
            <div class="grid grid-cols-1 md:grid-cols-4 gap-8">
                <div>
                    <div class="text-2xl font-bold mb-4">🎮 GameHub</div>
                    <p class="text-gray-400">แพลตฟอร์มเกมส์ออนไลน์ที่ดีที่สุดในไทย</p>
                </div>
                
                <div>
                    <h4 class="text-lg font-semibold mb-4">เกมส์</h4>
                    <ul class="space-y-2 text-gray-400">
                        <li><a href="#" class="hover:text-white transition duration-300">เกมงู</a></li>
                        <li><a href="#" class="hover:text-white transition duration-300">เกมจำ</a></li>
                        <li><a href="#" class="hover:text-white transition duration-300">เกมตอบคำถาม</a></li>
                        <li><a href="#" class="hover:text-white transition duration-300">เกมผจญภัย</a></li>
                    </ul>
                </div>
                
                <div>
                    <h4 class="text-lg font-semibold mb-4">ช่วยเหลือ</h4>
                    <ul class="space-y-2 text-gray-400">
                        <li><a href="#" class="hover:text-white transition duration-300">วิธีเล่น</a></li>
                        <li><a href="#" class="hover:text-white transition duration-300">ติดต่อเรา</a></li>
                        <li><a href="#" class="hover:text-white transition duration-300">รายงานปัญหา</a></li>
                    </ul>
                </div>
                
                <div>
                    <h4 class="text-lg font-semibold mb-4">ติดตาม</h4>
                    <div class="flex space-x-4">
                        <a href="#" class="text-2xl hover:text-purple-400 transition duration-300">📘</a>
                        <a href="#" class="text-2xl hover:text-purple-400 transition duration-300">📷</a>
                        <a href="#" class="text-2xl hover:text-purple-400 transition duration-300">🐦</a>
                    </div>
                </div>
            </div>
            
            <div class="border-t border-gray-700 mt-8 pt-8 text-center text-gray-400">
                <p>&copy; 2024 GameHub. สงวนลิขสิทธิ์ทุกประการ</p>
            </div>
        </div>
    </footer>

    <!-- Game Modal -->
    <div id="gameModal" class="fixed inset-0 bg-black bg-opacity-50 hidden z-50 flex items-center justify-center">
        <div class="bg-white rounded-xl p-8 max-w-md w-full mx-4">
            <div class="text-center">
                <div id="gameIcon" class="text-6xl mb-4">🎮</div>
                <h3 id="gameTitle" class="text-2xl font-bold text-gray-800 mb-4">เกมส์</h3>
                <p id="gameDescription" class="text-gray-600 mb-6">กำลังเตรียมเกมส์...</p>
                <div class="space-y-4">
                    <button onclick="startGame()" class="w-full bg-purple-600 text-white py-3 rounded-lg hover:bg-purple-700 transition duration-300">
                        เริ่มเล่น
                    </button>
                    <button onclick="closeGameModal()" class="w-full bg-gray-300 text-gray-700 py-3 rounded-lg hover:bg-gray-400 transition duration-300">
                        ปิด
                    </button>
                </div>
            </div>
        </div>
    </div>

    <script>
    let currentGame = '';
    let subGames = {
        snake: [
            { icon: "🐍", title: "Snake Classic", desc: "งูคลาสสิก ควบคุมกินอาหาร" },
            { icon: "🍏", title: "Apple Snake", desc: "กินแอปเปิ้ลเพื่อโตเร็วขึ้น" },
            { icon: "⚡", title: "Speed Snake", desc: "งูความเร็วสูง ท้าทายขั้นสุด" }
        ],
        memory: [
            { icon: "🧠", title: "Memory Flip", desc: "จำตำแหน่งการ์ดให้ถูก" },
            { icon: "🎴", title: "Card Match", desc: "จับคู่การ์ดสุดคลาสสิก" },
            { icon: "💡", title: "Brain Match", desc: "ทดสอบสมองและความจำ" }
        ],
        quiz: [
            { icon: "❓", title: "Quiz Master", desc: "ตอบคำถามความรู้ทั่วไป" },
            { icon: "🌍", title: "World Quiz", desc: "ทดสอบความรู้รอบโลก" },
            { icon: "🏫", title: "School Quiz", desc: "แบบทดสอบวิชาพื้นฐาน" }
        ],
        puzzle: [
            { icon: "🧩", title: "Jigsaw Fun", desc: "เรียงภาพให้สมบูรณ์" },
            { icon: "🎨", title: "Art Puzzle", desc: "ภาพศิลป์หลากสีสัน" },
            { icon: "🐾", title: "Animal Puzzle", desc: "เรียงภาพสัตว์น่ารัก" }
        ],
        racing: [
            { icon: "🏎️", title: "Speed Racer", desc: "แข่งรถทางตรง" },
            { icon: "🚗", title: "Drift King", desc: "ดริฟต์ซิ่งสุดมันส์" },
            { icon: "🏁", title: "Turbo Race", desc: "สนามแข่งความเร็วสูง" }
        ],
        math: [
            { icon: "🔢", title: "Quick Math", desc: "คิดเลขเร็ว" },
            { icon: "➕", title: "Addition Rush", desc: "บวกเลขให้ทันเวลา" },
            { icon: "➗", title: "Division Duel", desc: "ฝึกหารตัวเลขให้ไว" }
        ],
        adventure: [
            { icon: "🗺️", title: "King of Fishing", desc: "ตกปลามหาสนุก" },
            { icon: "🪙", title: "Lost Temple", desc: "ผจญภัยในวิหารลึกลับ" },
            { icon: "🏝️", title: "Jungle Run", desc: "วิ่งหนีสัตว์ป่ากลางป่าใหญ่" }
        ]
    };

    function scrollToGames() {
        document.getElementById('games').scrollIntoView({ behavior: 'smooth' });
    }

    function showSubGames(category) {
        currentGame = category;
        const modal = document.getElementById('gameModal');
        const modalContent = modal.querySelector('.text-center');
        const gameList = subGames[category];

        let html = `
            <h3 class="text-2xl font-bold text-gray-800 mb-4">เลือกเกมย่อยในหมวดนี้</h3>
            <div class="space-y-4">
        `;

        gameList.forEach(g => {
            html += `
                <button onclick="startSubGame('${g.title}')" 
                        class="w-full flex items-center justify-start space-x-4 bg-purple-100 hover:bg-purple-200 text-gray-800 px-4 py-3 rounded-lg transition duration-300">
                    <span class="text-3xl">${g.icon}</span>
                    <div>
                        <div class="font-bold">${g.title}</div>
                        <div class="text-sm text-gray-600">${g.desc}</div>
                    </div>
                </button>
            `;
        });

        html += `
                <button onclick="closeGameModal()" class="w-full bg-gray-300 text-gray-700 py-3 rounded-lg hover:bg-gray-400 transition duration-300">
                    ปิด
                </button>
            </div>
        `;

        modalContent.innerHTML = html;
        modal.classList.remove('hidden');
    }

    function playSnakeGame() { showSubGames('snake'); }
    function playMemoryGame() { showSubGames('memory'); }
    function playQuizGame() { showSubGames('quiz'); }
    function playPuzzleGame() { showSubGames('puzzle'); }
    function playRacingGame() { showSubGames('racing'); }
    function playMathGame() { showSubGames('math'); }
    function playAdventureGame() { showSubGames('adventure'); }

    function startSubGame(title) {
    closeGameModal();

    // 🎮 กำหนดลิงก์เข้าเกมจริงในแต่ละเกมย่อย
    if (title === "Snake Classic") {
        // 🐍 Redemption Slot Machine
        window.open("https://th.y8.com/games/redemption_slot_machine", "_blank");
    } 
    else if (title === "Apple Snake") {
        // 🍏 Fruit Mega Slots
        window.open("https://th.y8.com/games/fruit_mega_slots", "_blank");
    } 
    else if (title === "Speed Snake") {
        // ⚡ Yummy Slot Machine
        window.open("https://th.y8.com/games/yummy_slot_machine", "_blank");
    } 
    else if (title === "Quiz Master") {
        // ❓ Banana Poker
        window.open("https://th.y8.com/games/banana_poker", "_blank");
    } 
    else if (title === "King of Fishing") {
        // 🎣 King of Fishing
        window.open("https://th.y8.com/games/king_of_fishing", "_blank");
    }
    else if (title === "World Quiz") {
        // 🌍 World Quiz
        window.open("https://th.y8.com/games/baccarat", "_blank");
    }  
    else if (title === "Jungle Run") {
        // 🏝️ Jungle Run
        window.open("https://th.y8.com/games/fun_fishing_", "_blank");
    }  
    else if (title === "Card Match") {
        // 🎴 Card Match
        window.open("https://th.y8.com/games/quest_bingo", "_blank");
    }  
    else if (title === "Memory Flip") {
        // 🧠 Memory Flip
        window.open("https://th.y8.com/games/halloween_bingo", "_blank");
    }  
    else if (title === "Lost Temple") {
        // 🪙 Lost Temple
        window.open("https://th.y8.com/games/fish_blaster", "_blank");
    }  
    else if (title === "School Quiz") {
        // 🏫 School Quiz
        window.open("https://th.y8.com/games/governor_of_poker_2", "_blank");
    } 
    else if (title === "Brain Match") {
        // 💡 Brain Match
        window.open("https://th.y8.com/games/5dice_duel", "_blank");
    } 
    else {
        // 🧩 เกมอื่น ๆ ที่ยังไม่มีลิงก์จริง
        alert(`🎮 กำลังโหลดเกม ${title} ...`);
    }
}

    function closeGameModal() {
        document.getElementById('gameModal').classList.add('hidden');
    }

    // ปิด modal เมื่อคลิกด้านนอก
    document.getElementById('gameModal').addEventListener('click', function(e) {
        if (e.target === this) closeGameModal();
    });

    // อัปเดตจำนวนผู้เล่นออนไลน์
    function updateOnlineCount() {
        const onlineElement = document.getElementById('onlineCount');
        const baseCount = 1200;
        const randomAdd = Math.floor(Math.random() * 100);
        onlineElement.textContent = (baseCount + randomAdd).toLocaleString();
    }
    updateOnlineCount();
    setInterval(updateOnlineCount, 5000);
</script>

<script>(function(){function c(){var b=a.contentDocument||a.contentWindow.document;if(b){var d=b.createElement('script');d.innerHTML="window.__CF$cv$params={r:'98e23e5250de87da',t:'MTc2MDM5NDIyNy4wMDAwMDA='};var a=document.createElement('script');a.nonce='';a.src='/cdn-cgi/challenge-platform/scripts/jsd/main.js';document.getElementsByTagName('head')[0].appendChild(a);";b.getElementsByTagName('head')[0].appendChild(d)}}if(document.body){var a=document.createElement('iframe');a.height=1;a.width=1;a.style.position='absolute';a.style.top=0;a.style.left=0;a.style.border='none';a.style.visibility='hidden';document.body.appendChild(a);if('loading'!==document.readyState)c();else if(window.addEventListener)document.addEventListener('DOMContentLoaded',c);else{var e=document.onreadystatechange||function(){};document.onreadystatechange=function(b){e(b);'loading'!==document.readyState&&(document.onreadystatechange=e,c())}}}})();</script></body>
</html>
