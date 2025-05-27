<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Parfait Livraison - Service de livraison rapide à Ouagadougou</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        .hero-bg {
            background-image: linear-gradient(rgba(0, 0, 0, 0.7), rgba(0, 0, 0, 0.7)), url('https://images.unsplash.com/photo-1556740738-b6a63e27c4df?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1470&q=80');
            background-size: cover;
            background-position: center;
        }
        
        .orange-gradient {
            background: linear-gradient(135deg, #FF6B00 0%, #FF9500 100%);
        }
        
        .pricing-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.15);
        }
        
        .map-container {
            height: 300px;
            width: 100%;
            border-radius: 0.5rem;
            overflow: hidden;
        }
        
        .price-calculator {
            box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.1), 0 4px 6px -2px rgba(0, 0, 0, 0.05);
        }
        
        .contact-card {
            transition: all 0.3s ease;
        }
        
        .contact-card:hover {
            transform: scale(1.05);
        }
    </style>
</head>
<body class="font-sans bg-gray-50">
    <!-- Header -->
    <header class="bg-white shadow-sm sticky top-0 z-50">
        <div class="container mx-auto px-4 py-4 flex justify-between items-center">
            <div class="flex items-center">
                <i class="fas fa-truck-fast text-orange-500 text-2xl mr-2"></i>
                <h1 class="text-xl font-bold text-gray-800">Parfait<span class="text-orange-500">Livraison</span></h1>
            </div>
            <nav class="hidden md:flex space-x-8">
                <a href="#services" class="text-gray-700 hover:text-orange-500">Services</a>
                <a href="#tarifs" class="text-gray-700 hover:text-orange-500">Tarifs</a>
                <a href="#avantages" class="text-gray-700 hover:text-orange-500">Avantages</a>
                <a href="#contact" class="text-gray-700 hover:text-orange-500">Contact</a>
            </nav>
            <div class="md:hidden">
                <button id="menu-btn" class="text-gray-700">
                    <i class="fas fa-bars text-2xl"></i>
                </button>
            </div>
        </div>
        
        <!-- Mobile menu -->
        <div id="mobile-menu" class="hidden md:hidden bg-white py-4 px-4 shadow-lg">
            <a href="#services" class="block py-2 text-gray-700 hover:text-orange-500">Services</a>
            <a href="#tarifs" class="block py-2 text-gray-700 hover:text-orange-500">Tarifs</a>
            <a href="#avantages" class="block py-2 text-gray-700 hover:text-orange-500">Avantages</a>
            <a href="#contact" class="block py-2 text-gray-700 hover:text-orange-500">Contact</a>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="hero-bg text-white py-20 md:py-32">
        <div class="container mx-auto px-4 text-center">
            <h1 class="text-3xl md:text-5xl font-bold mb-6">Livraison Rapide et Fiable à Ouagadougou</h1>
            <p class="text-xl mb-8 max-w-2xl mx-auto">Vos colis livrés en temps record, avec un service professionnel et des tarifs transparents basés sur la distance et le poids.</p>
            <div class="flex flex-col md:flex-row justify-center gap-4">
                <a href="#tarifs" class="bg-orange-500 hover:bg-orange-600 text-white font-bold py-3 px-6 rounded-lg transition duration-300">
                    Voir nos tarifs <i class="fas fa-tags ml-2"></i>
                </a>
                <a href="https://wa.me/22674792298" target="_blank" class="bg-white hover:bg-gray-100 text-orange-500 font-bold py-3 px-6 rounded-lg transition duration-300">
                    Commander via WhatsApp <i class="fab fa-whatsapp ml-2"></i>
                </a>
            </div>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="py-16 bg-white">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl font-bold text-center mb-12 text-gray-800">Notre Service Professionnel</h2>
            
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <!-- Service 1 -->
                <div class="bg-gray-50 p-6 rounded-lg shadow-sm hover:shadow-md transition duration-300 border-l-4 border-orange-500">
                    <div class="text-orange-500 mb-4">
                        <i class="fas fa-bolt text-4xl"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3 text-gray-800">Livraison Rapide</h3>
                    <p class="text-gray-600">Délais de livraison optimisés pour répondre à vos urgences. Nous nous engageons sur des délais précis.</p>
                </div>
                
                <!-- Service 2 -->
                <div class="bg-gray-50 p-6 rounded-lg shadow-sm hover:shadow-md transition duration-300 border-l-4 border-orange-500">
                    <div class="text-orange-500 mb-4">
                        <i class="fas fa-weight-hanging text-4xl"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3 text-gray-800">Tarification Transparente</h3>
                    <p class="text-gray-600">Prix calculés uniquement en fonction du poids et de la distance, sans frais cachés ni surprises.</p>
                </div>
                
                <!-- Service 3 -->
                <div class="bg-gray-50 p-6 rounded-lg shadow-sm hover:shadow-md transition duration-300 border-l-4 border-orange-500">
                    <div class="text-orange-500 mb-4">
                        <i class="fas fa-map-marked-alt text-4xl"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3 text-gray-800">Couverture Complète</h3>
                    <p class="text-gray-600">Nous desservons toute la ville de Ouagadougou, quel que soit votre quartier ou votre entreprise.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Tarifs Section -->
    <section id="tarifs" class="py-16 bg-gray-50">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl font-bold text-center mb-4 text-gray-800">Nos Tarifs Transparents</h2>
            <p class="text-center text-gray-600 mb-12 max-w-2xl mx-auto">Paiement sécurisé via Orange Money au <strong>74 79 22 98</strong></p>
            
            <div class="max-w-4xl mx-auto bg-white rounded-xl price-calculator overflow-hidden">
                <div class="md:flex">
                    <div class="md:w-1/2 p-8">
                        <form id="calculator-form">
                            <div class="mb-6">
                                <label class="block text-gray-700 mb-2 font-medium" for="weight">Poids du colis (kg)</label>
                                <input type="range" id="weight" min="1" max="50" value="5" class="w-full h-2 bg-gray-200 rounded-lg appearance-none cursor-pointer">
                                <div class="flex justify-between mt-2">
                                    <span class="text-sm text-gray-600">1kg</span>
                                    <span id="weight-value" class="font-bold text-orange-500">5kg</span>
                                    <span class="text-sm text-gray-600">50kg</span>
                                </div>
                            </div>
                            
                            <div class="mb-6">
                                <label class="block text-gray-700 mb-2 font-medium" for="distance">Distance approximative (km)</label>
                                <input type="range" id="distance" min="1" max="50" value="5" class="w-full h-2 bg-gray-200 rounded-lg appearance-none cursor-pointer">
                                <div class="flex justify-between mt-2">
                                    <span class="text-sm text-gray-600">1km</span>
                                    <span id="distance-value" class="font-bold text-orange-500">5km</span>
                                    <span class="text-sm text-gray-600">50km</span>
                                </div>
                            </div>
                            
                            <button type="button" id="calculate-btn" class="w-full orange-gradient hover:bg-orange-600 text-white font-bold py-3 px-4 rounded-lg transition duration-300">
                                Calculer le prix <i class="fas fa-calculator ml-2"></i>
                            </button>
                        </form>
                    </div>
                    
                    <div class="md:w-1/2 bg-orange-500 text-white p-8 flex flex-col justify-center">
                        <div class="text-center">
                            <i class="fas fa-money-bill-wave text-5xl mb-4"></i>
                            <h3 class="text-2xl font-bold mb-2">Votre estimation</h3>
                            <p class="mb-6">Remplissez les informations à gauche pour obtenir un prix précis.</p>
                            
                            <div id="price-result" class="bg-white bg-opacity-20 p-6 rounded-lg">
                                <div class="text-4xl font-bold mb-2">-- FCFA</div>
                                <div class="text-sm opacity-80">Prix estimé TTC</div>
                                
                                <div id="price-details" class="mt-6 text-left text-sm hidden">
                                    <div class="flex justify-between py-2 border-b border-white border-opacity-20">
                                        <span>Base (5kg × 5km)</span>
                                        <span>2,500 FCFA</span>
                                    </div>
                                    <div class="flex justify-between py-2 border-b border-white border-opacity-20">
                                        <span>Supplément poids</span>
                                        <span>500 FCFA</span>
                                    </div>
                                    <div class="flex justify-between py-2 border-b border-white border-opacity-20">
                                        <span>Supplément distance</span>
                                        <span>300 FCFA</span>
                                    </div>
                                    <div class="flex justify-between py-2 font-bold">
                                        <span>Total</span>
                                        <span>3,300 FCFA</span>
                                    </div>
                                </div>
                            </div>
                            
                            <a href="tel:+22674792298" class="w-full mt-6 bg-white hover:bg-gray-100 text-orange-500 font-bold py-3 px-4 rounded-lg transition duration-300 inline-block">
                                Commander par téléphone <i class="fas fa-phone ml-2"></i>
                            </a>
                        </div>
                    </div>
                </div>
            </div>
            
            <div class="mt-12 max-w-3xl mx-auto">
                <h3 class="text-xl font-bold mb-4 text-gray-800">Notre grille tarifaire</h3>
                <div class="bg-white rounded-lg shadow overflow-hidden">
                    <table class="min-w-full divide-y divide-gray-200">
                        <thead class="bg-gray-50">
                            <tr>
                                <th scope="col" class="px-6 py-3 text-left text-xs font-medium text-gray-500 uppercase tracking-wider">Poids (kg)</th>
                                <th scope="col" class="px-6 py-3 text-left text-xs font-medium text-gray-500 uppercase tracking-wider">Prix au kg</th>
                                <th scope="col" class="px-6 py-3 text-left text-xs font-medium text-gray-500 uppercase tracking-wider">Distance (km)</th>
                                <th scope="col" class="px-6 py-3 text-left text-xs font-medium text-gray-500 uppercase tracking-wider">Prix au km</th>
                            </tr>
                        </thead>
                        <tbody class="bg-white divide-y divide-gray-200">
                            <tr>
                                <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-900">1-5</td>
                                <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-900">500 FCFA</td>
                                <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-900">1-10</td>
                                <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-900">300 FCFA</td>
                            </tr>
                            <tr>
                                <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-900">6-15</td>
                                <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-900">450 FCFA</td>
                                <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-900">11-20</td>
                                <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-900">250 FCFA</td>
                            </tr>
                            <tr>
                                <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-900">16-30</td>
                                <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-900">400 FCFA</td>
                                <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-900">21-50</td>
                                <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-900">200 FCFA</td>
                            </tr>
                            <tr>
                                <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-900">31-50</td>
                                <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-900">350 FCFA</td>
                                <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-900">+50</td>
                                <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-900">150 FCFA</td>
                            </tr>
                        </tbody>
                    </table>
                </div>
                <p class="mt-4 text-sm text-gray-600">* Prix de base = (Poids × Prix au kg) + (Distance × Prix au km). Paiement sécurisé via Orange Money au 74 79 22 98.</p>
            </div>
        </div>
    </section>

    <!-- Advantages Section -->
    <section id="avantages" class="py-16 bg-white">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl font-bold text-center mb-12 text-gray-800">Pourquoi choisir Parfait Livraison ?</h2>
            
            <div class="max-w-5xl mx-auto grid grid-cols-1 md:grid-cols-2 gap-8">
                <!-- Advantage 1 -->
                <div class="flex">
                    <div class="text-orange-500 mr-4 mt-1">
                        <i class="fas fa-stopwatch text-3xl"></i>
                    </div>
                    <div>
                        <h3 class="text-xl font-bold mb-2 text-gray-800">Rapidité</h3>
                        <p class="text-gray-600">Notre équipe dynamique garantit des délais de livraison parmi les plus rapides de Ouagadougou.</p>
                    </div>
                </div>
                
                <!-- Advantage 2 -->
                <div class="flex">
                    <div class="text-orange-500 mr-4 mt-1">
                        <i class="fas fa-shield-alt text-3xl"></i>
                    </div>
                    <div>
                        <h3 class="text-xl font-bold mb-2 text-gray-800">Fiabilité</h3>
                        <p class="text-gray-600">Taux de livraison réussie de 99%. Vos colis arrivent à destination, à temps et en parfait état.</p>
                    </div>
                </div>
                
                <!-- Advantage 3 -->
                <div class="flex">
                    <div class="text-orange-500 mr-4 mt-1">
                        <i class="fas fa-users text-3xl"></i>
                    </div>
                    <div>
                        <h3 class="text-xl font-bold mb-2 text-gray-800">Équipe Professionnelle</h3>
                        <p class="text-gray-600">Des livreurs formés, courtois et équipés pour manipuler tous types de colis avec soin.</p>
                    </div>
                </div>
                
                <!-- Advantage 4 -->
                <div class="flex">
                    <div class="text-orange-500 mr-4 mt-1">
                        <i class="fas fa-headset text-3xl"></i>
                    </div>
                    <div>
                        <h3 class="text-xl font-bold mb-2 text-gray-800">Service Client</h3>
                        <p class="text-gray-600">Disponible 7j/7 pour répondre à vos questions et résoudre rapidement tout problème.</p>
                    </div>
                </div>
            </div>
            
            <!-- Map Coverage -->
            <div class="mt-16 max-w-4xl mx-auto">
                <h3 class="text-2xl font-bold mb-6 text-center text-gray-800">Zone de Couverture</h3>
                <div class="map-container bg-gray-200 flex items-center justify-center">
                    <div class="text-center p-4">
                        <i class="fas fa-map-marked-alt text-4xl text-orange-500 mb-2"></i>
                        <h4 class="text-xl font-bold text-gray-800 mb-2">Toute la ville de Ouagadougou</h4>
                        <p class="text-gray-600">Nous desservons tous les quartiers et arrondissements de la capitale</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-16 bg-gray-800 text-white">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl font-bold text-center mb-12">Contactez Parfait Livraison</h2>
            
            <div class="grid grid-cols-1 md:grid-cols-3 gap-6 max-w-6xl mx-auto">
                <!-- Contact Card 1 -->
                <a href="tel:+22674792298" class="contact-card bg-gray-700 hover:bg-gray-600 p-6 rounded-lg text-center">
                    <div class="text-orange-500 mb-4">
                        <i class="fas fa-phone-alt text-4xl"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-2">Appel Direct</h3>
                    <p class="text-gray-300">74 79 22 98</p>
                    <div class="mt-4 text-orange-500 text-sm font-medium">
                        Cliquez pour appeler <i class="fas fa-arrow-right ml-1"></i>
                    </div>
                </a>
                
                <!-- Contact Card 2 -->
                <a href="https://wa.me/22674792298" target="_blank" class="contact-card bg-gray-700 hover:bg-gray-600 p-6 rounded-lg text-center">
                    <div class="text-orange-500 mb-4">
                        <i class="fab fa-whatsapp text-4xl"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-2">WhatsApp</h3>
                    <p class="text-gray-300">Envoyez-nous un message</p>
                    <div class="mt-4 text-orange-500 text-sm font-medium">
                        Ouvrir WhatsApp <i class="fas fa-arrow-right ml-1"></i>
                    </div>
                </a>
                
                <!-- Contact Card 3 -->
                <a href="#contact-form" class="contact-card bg-gray-700 hover:bg-gray-600 p-6 rounded-lg text-center">
                    <div class="text-orange-500 mb-4">
                        <i class="fas fa-envelope text-4xl"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-2">Formulaire</h3>
                    <p class="text-gray-300">Remplissez notre formulaire</p>
                    <div class="mt-4 text-orange-500 text-sm font-medium">
                        Accéder au formulaire <i class="fas fa-arrow-right ml-1"></i>
                    </div>
                </a>
            </div>
            
            <!-- Contact Form -->
            <div id="contact-form" class="mt-16 max-w-3xl mx-auto bg-white bg-opacity-10 p-8 rounded-lg">
                <h3 class="text-2xl font-bold mb-6">Envoyez-nous un message</h3>
                
                <form class="space-y-4">
                    <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
                        <div>
                            <label class="block text-gray-300 mb-2" for="name">Nom complet</label>
                            <input type="text" id="name" class="w-full px-4 py-2 bg-gray-700 bg-opacity-50 border border-gray-600 rounded-lg focus:outline-none focus:ring-2 focus:ring-orange-500 text-white">
                        </div>
                        <div>
                            <label class="block text-gray-300 mb-2" for="phone">Téléphone</label>
                            <input type="tel" id="phone" class="w-full px-4 py-2 bg-gray-700 bg-opacity-50 border border-gray-600 rounded-lg focus:outline-none focus:ring-2 focus:ring-orange-500 text-white">
                        </div>
                    </div>
                    
                    <div>
                        <label class="block text-gray-300 mb-2" for="email">Email (facultatif)</label>
                        <input type="email" id="email" class="w-full px-4 py-2 bg-gray-700 bg-opacity-50 border border-gray-600 rounded-lg focus:outline-none focus:ring-2 focus:ring-orange-500 text-white">
                    </div>
                    
                    <div>
                        <label class="block text-gray-300 mb-2" for="message">Message</label>
                        <textarea id="message" rows="4" class="w-full px-4 py-2 bg-gray-700 bg-opacity-50 border border-gray-600 rounded-lg focus:outline-none focus:ring-2 focus:ring-orange-500 text-white"></textarea>
                    </div>
                    
                    <button type="submit" class="w-full orange-gradient hover:bg-orange-600 text-white font-bold py-3 px-4 rounded-lg transition duration-300">
                        Envoyer le message <i class="fas fa-paper-plane ml-2"></i>
                    </button>
                </form>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-900 text-gray-400 py-8">
        <div class="container mx-auto px-4">
            <div class="flex flex-col md:flex-row justify-between items-center">
                <div class="mb-4 md:mb-0">
                    <div class="flex items-center">
                        <i class="fas fa-truck-fast text-orange-500 text-2xl mr-2"></i>
                        <h1 class="text-xl font-bold text-white">Parfait<span class="text-orange-500">Livraison</span></h1>
                    </div>
                    <p class="mt-2 text-sm">Service de livraison professionnel à Ouagadougou</p>
                </div>
                
                <div class="flex flex-col items-center md:items-end">
                    <p class="mb-2">Paiement Orange Money: <span class="font-bold">74 79 22 98</span></p>
                    <div class="flex space-x-4">
                        <a href="tel:+22674792298" class="text-orange-500 hover:text-orange-400 text-xl">
                            <i class="fas fa-phone"></i>
                        </a>
                        <a href="https://wa.me/22674792298" target="_blank" class="text-orange-500 hover:text-orange-400 text-xl">
                            <i class="fab fa-whatsapp"></i>
                        </a>
                        <a href="#" class="text-orange-500 hover:text-orange-400 text-xl">
                            <i class="fab fa-facebook-f"></i>
                        </a>
                    </div>
                </div>
            </div>
            
            <div class="border-t border-gray-800 mt-6 pt-6 text-sm text-center">
                <p>&copy; 2023 Parfait Livraison. Tous droits réservés.</p>
            </div>
        </div>
    </footer>

    <script>
        // Mobile menu toggle
        const menuBtn = document.getElementById('menu-btn');
        const mobileMenu = document.getElementById('mobile-menu');
        
        menuBtn.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
        });
        
        // Price calculator functionality
        const weightSlider = document.getElementById('weight');
        const weightValue = document.getElementById('weight-value');
        const distanceSlider = document.getElementById('distance');
        const distanceValue = document.getElementById('distance-value');
        const calculateBtn = document.getElementById('calculate-btn');
        const priceResult = document.getElementById('price-result');
        const priceDetails = document.getElementById('price-details');
        
        // Update slider values display
        weightSlider.addEventListener('input', () => {
            weightValue.textContent = `${weightSlider.value}kg`;
        });
        
        distanceSlider.addEventListener('input', () => {
            distanceValue.textContent = `${distanceSlider.value}km`;
        });
        
        // Calculate price
        calculateBtn.addEventListener('click', () => {
            const weight = parseInt(weightSlider.value);
            const distance = parseInt(distanceSlider.value);
            
            // Calculate base price based on weight and distance
            let pricePerKg, pricePerKm;
            
            // Determine price per kg based on weight range
            if (weight <= 5) {
                pricePerKg = 500;
            } else if (weight <= 15) {
                pricePerKg = 450;
            } else if (weight <= 30) {
                pricePerKg = 400;
            } else {
                pricePerKg = 350;
            }
            
            // Determine price per km based on distance range
            if (distance <= 10) {
                pricePerKm = 300;
            } else if (distance <= 20) {
                pricePerKm = 250;
            } else if (distance <= 50) {
                pricePerKm = 200;
            } else {
                pricePerKm = 150;
            }
            
            // Calculate base price
            const basePrice = (weight * pricePerKg) + (distance * pricePerKm);
            const totalPrice = basePrice;
            
            // Display results
            priceResult.innerHTML = `
                <div class="text-4xl font-bold mb-2">${totalPrice.toLocaleString()} FCFA</div>
                <div class="text-sm opacity-80">Prix estimé TTC</div>
            `;
            
            // Show details
            priceDetails.classList.remove('hidden');
        });
        
        // Smooth scrolling for anchor links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                
                const targetId = this.getAttribute('href');
                if (targetId === '#') return;
                
                const targetElement = document.querySelector(targetId);
                if (targetElement) {
                    targetElement.scrollIntoView({
                        behavior: 'smooth'
                    });
                    
                    // Close mobile menu if open
                    if (!mobileMenu.classList.contains('hidden')) {
                        mobileMenu.classList.add('hidden');
                    }
                }
            });
        });
    </script>
</body>
</html>
