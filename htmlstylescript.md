<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Black Peak Digital | High-Conversion Leads for Local Businesses</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&family=Space+Grotesk:wght@600;700&display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        :root {
            --primary-green: #1a4d47;
            --deep-green: #0f2e2a;
            --teal-dark: #1a4d47;
            --teal-medium: #2a5d57;
            --accent-gold: #d4af6a;
            --accent-gold-light: #e5c589;
            --accent-gold-glow: rgba(212, 175, 106, 0.4);
            --text-light: #ffffff;
            --text-muted: #9cb3ae;
            --bg-dark: #0a1e1b;
            --card-bg: linear-gradient(135deg, rgba(26, 77, 71, 0.15) 0%, rgba(42, 93, 87, 0.08) 100%);
            --border-gradient: linear-gradient(135deg, rgba(212, 175, 106, 0.3) 0%, rgba(26, 77, 71, 0.3) 100%);
            --glow-gradient: radial-gradient(circle at 50% 50%, rgba(212, 175, 106, 0.15) 0%, transparent 70%);
        }

        body {
            font-family: 'Inter', sans-serif;
            background: radial-gradient(ellipse at top, #0f2e2a 0%, #0a1e1b 50%, #050f0e 100%);
            color: var(--text-light);
            line-height: 1.6;
            overflow-x: hidden;
        }

        h1, h2, h3 {
            font-family: 'Space Grotesk', sans-serif;
            font-weight: 700;
            line-height: 1.1;
        }

        .container {
            max-width: 1280px;
            margin: 0 auto;
            padding: 0 2rem;
        }

        /* Header */
        header {
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 1000;
            background: linear-gradient(180deg, rgba(10, 30, 27, 0.95) 0%, rgba(10, 30, 27, 0.85) 100%);
            backdrop-filter: blur(20px);
            border-bottom: 1px solid;
            border-image: linear-gradient(90deg, transparent 0%, rgba(212, 175, 106, 0.3) 50%, transparent 100%) 1;
            transition: all 0.3s ease;
        }

        header.scrolled {
            background: linear-gradient(180deg, rgba(10, 30, 27, 0.98) 0%, rgba(10, 30, 27, 0.95) 100%);
            box-shadow: 0 8px 32px rgba(0, 0, 0, 0.3);
        }

        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 1.5rem 2rem;
            max-width: 1280px;
            margin: 0 auto;
        }

        .logo {
            font-size: 1.5rem;
            font-weight: 700;
            background: linear-gradient(135deg, var(--accent-gold-light) 0%, var(--accent-gold) 100%);
            -webkit-background-clip: text;
            background-clip: text;
            -webkit-text-fill-color: transparent;
            display: flex;
            align-items: center;
            gap: 0.5rem;
            filter: drop-shadow(0 0 20px rgba(212, 175, 106, 0.3));
            transition: all 0.3s ease;
        }

        .logo:hover {
            filter: drop-shadow(0 0 30px rgba(212, 175, 106, 0.5));
            transform: translateY(-2px);
        }

        .logo::before {
            content: "▲";
            font-size: 1.8rem;
            background: linear-gradient(135deg, var(--accent-gold-light) 0%, var(--accent-gold) 100%);
            -webkit-background-clip: text;
            background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .nav-links {
            display: flex;
            gap: 3rem;
            list-style: none;
        }

        .nav-links a {
            color: var(--text-muted);
            text-decoration: none;
            font-weight: 500;
            font-size: 0.95rem;
            transition: color 0.3s ease;
            position: relative;
        }

        .nav-links a:hover {
            color: var(--text-light);
        }

        .nav-links a::after {
            content: '';
            position: absolute;
            bottom: -5px;
            left: 0;
            width: 0;
            height: 2px;
            background: linear-gradient(90deg, var(--accent-gold) 0%, var(--accent-gold-light) 100%);
            transition: width 0.3s ease;
            box-shadow: 0 0 10px var(--accent-gold-glow);
        }

        .nav-links a:hover::after {
            width: 100%;
        }

        .btn {
            padding: 0.875rem 2rem;
            border-radius: 8px;
            font-weight: 600;
            text-decoration: none;
            transition: all 0.3s ease;
            display: inline-block;
            border: none;
            cursor: pointer;
            font-size: 0.95rem;
        }

        .btn-primary {
            background: linear-gradient(135deg, var(--accent-gold-light) 0%, var(--accent-gold) 100%);
            color: var(--deep-green);
            box-shadow: 0 4px 20px var(--accent-gold-glow);
            position: relative;
            overflow: hidden;
        }

        .btn-primary::before {
            content: '';
            position: absolute;
            top: 0;
            left: -100%;
            width: 100%;
            height: 100%;
            background: linear-gradient(90deg, transparent, rgba(255, 255, 255, 0.3), transparent);
            transition: left 0.5s ease;
        }

        .btn-primary:hover::before {
            left: 100%;
        }

        .btn-primary:hover {
            transform: translateY(-2px);
            box-shadow: 0 8px 30px var(--accent-gold-glow);
        }

        .btn-secondary {
            background: transparent;
            border: 2px solid transparent;
            background-image: linear-gradient(var(--bg-dark), var(--bg-dark)), var(--border-gradient);
            background-origin: border-box;
            background-clip: padding-box, border-box;
            color: var(--text-light);
            position: relative;
            overflow: hidden;
        }

        .btn-secondary::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: var(--card-bg);
            opacity: 0;
            transition: opacity 0.3s ease;
        }

        .btn-secondary:hover::before {
            opacity: 1;
        }

        .btn-secondary:hover {
            transform: translateY(-2px);
            box-shadow: 0 8px 30px rgba(212, 175, 106, 0.2);
        }

        /* Hero Section */
        .hero {
            min-height: 100vh;
            display: flex;
            align-items: center;
            position: relative;
            padding: 8rem 0 4rem;
            overflow: hidden;
        }

        .hero::before {
            content: '';
            position: absolute;
            top: -20%;
            right: -10%;
            width: 800px;
            height: 800px;
            background: radial-gradient(circle, rgba(26, 77, 71, 0.4) 0%, transparent 70%);
            border-radius: 50%;
            filter: blur(80px);
            animation: float 20s ease-in-out infinite;
        }

        .hero::after {
            content: '';
            position: absolute;
            bottom: -20%;
            left: -10%;
            width: 700px;
            height: 700px;
            background: radial-gradient(circle, rgba(212, 175, 106, 0.2) 0%, transparent 70%);
            border-radius: 50%;
            filter: blur(100px);
            animation: float 25s ease-in-out infinite reverse;
        }

        @keyframes float {
            0%, 100% { transform: translate(0, 0) scale(1); }
            50% { transform: translate(30px, -30px) scale(1.1); }
        }

        .hero-content {
            position: relative;
            z-index: 2;
            max-width: 900px;
        }

        .badge {
            display: inline-flex;
            align-items: center;
            padding: 0.5rem 1.25rem;
            background: linear-gradient(135deg, rgba(212, 175, 106, 0.15) 0%, rgba(26, 77, 71, 0.15) 100%);
            border: 1px solid;
            border-image: var(--border-gradient) 1;
            border-radius: 50px;
            color: var(--accent-gold-light);
            font-size: 0.875rem;
            font-weight: 600;
            letter-spacing: 0.5px;
            margin-bottom: 2rem;
            box-shadow: 0 4px 20px rgba(212, 175, 106, 0.1);
            animation: pulse 3s ease-in-out infinite;
        }

        @keyframes pulse {
            0%, 100% { box-shadow: 0 4px 20px rgba(212, 175, 106, 0.1); }
            50% { box-shadow: 0 4px 30px rgba(212, 175, 106, 0.3); }
        }

        .hero h1 {
            font-size: 5rem;
            margin-bottom: 1.5rem;
            background: linear-gradient(135deg, #ffffff 0%, var(--accent-gold-light) 50%, var(--text-muted) 100%);
            -webkit-background-clip: text;
            background-clip: text;
            -webkit-text-fill-color: transparent;
            line-height: 1.1;
            animation: fadeInUp 0.8s ease-out;
            text-shadow: 0 0 80px rgba(212, 175, 106, 0.3);
        }

        .hero p {
            font-size: 1.25rem;
            color: var(--text-muted);
            margin-bottom: 3rem;
            max-width: 700px;
            line-height: 1.7;
        }

        .hero-actions {
            display: flex;
            gap: 1.5rem;
            flex-wrap: wrap;
        }

        /* Stats */
        .stats {
            display: grid;
            grid-template-columns: repeat(4, 1fr);
            gap: 2rem;
            margin-top: 6rem;
        }

        .stat-item {
            text-align: center;
            padding: 2rem;
            background: var(--card-bg);
            border: 2px solid transparent;
            background-image: linear-gradient(135deg, rgba(26, 77, 71, 0.15) 0%, rgba(42, 93, 87, 0.08) 100%), var(--border-gradient);
            background-origin: border-box;
            background-clip: padding-box, border-box;
            border-radius: 16px;
            transition: all 0.4s ease;
            position: relative;
            overflow: hidden;
        }

        .stat-item::before {
            content: '';
            position: absolute;
            top: 0;
            left: -100%;
            width: 100%;
            height: 100%;
            background: linear-gradient(90deg, transparent, rgba(212, 175, 106, 0.1), transparent);
            transition: left 0.6s ease;
        }

        .stat-item:hover::before {
            left: 100%;
        }

        .stat-item:hover {
            transform: translateY(-8px) scale(1.02);
            box-shadow: 0 20px 40px rgba(212, 175, 106, 0.2);
        }

        .stat-number {
            font-size: 3rem;
            font-weight: 700;
            background: linear-gradient(135deg, var(--accent-gold-light) 0%, var(--accent-gold) 100%);
            -webkit-background-clip: text;
            background-clip: text;
            -webkit-text-fill-color: transparent;
            font-family: 'Space Grotesk', sans-serif;
            margin-bottom: 0.5rem;
            filter: drop-shadow(0 0 20px rgba(212, 175, 106, 0.3));
        }

        .stat-label {
            color: var(--text-muted);
            font-size: 0.95rem;
        }

        /* Section */
        .section {
            padding: 8rem 0;
            position: relative;
        }

        .section-header {
            text-align: center;
            max-width: 700px;
            margin: 0 auto 5rem;
        }

        .section-label {
            background: linear-gradient(135deg, var(--accent-gold-light) 0%, var(--accent-gold) 100%);
            -webkit-background-clip: text;
            background-clip: text;
            -webkit-text-fill-color: transparent;
            font-size: 0.875rem;
            font-weight: 600;
            letter-spacing: 2px;
            text-transform: uppercase;
            margin-bottom: 1rem;
            display: inline-block;
        }

        .section-header h2 {
            font-size: 3.5rem;
            margin-bottom: 1.5rem;
            background: linear-gradient(135deg, #ffffff 0%, var(--text-muted) 100%);
            -webkit-background-clip: text;
            background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .section-header p {
            font-size: 1.15rem;
            color: var(--text-muted);
        }

        /* Cards Grid */
        .cards-grid {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 2rem;
        }

        .card {
            background: var(--card-bg);
            border: 2px solid transparent;
            background-image: linear-gradient(135deg, rgba(26, 77, 71, 0.15) 0%, rgba(42, 93, 87, 0.08) 100%), var(--border-gradient);
            background-origin: border-box;
            background-clip: padding-box, border-box;
            padding: 3rem;
            border-radius: 24px;
            transition: all 0.5s cubic-bezier(0.4, 0, 0.2, 1);
            position: relative;
            overflow: hidden;
        }

        .card::before {
            content: '';
            position: absolute;
            top: -50%;
            left: -50%;
            width: 200%;
            height: 200%;
            background: radial-gradient(circle, rgba(212, 175, 106, 0.15) 0%, transparent 60%);
            opacity: 0;
            transition: all 0.5s ease;
            transform: scale(0.5);
        }

        .card:hover::before {
            opacity: 1;
            transform: scale(1);
        }

        .card:hover {
            transform: translateY(-10px);
            box-shadow: 0 20px 60px rgba(212, 175, 106, 0.2), 0 0 40px rgba(26, 77, 71, 0.3);
        }

        .card-icon {
            font-size: 3rem;
            margin-bottom: 1.5rem;
            display: block;
            filter: drop-shadow(0 0 20px rgba(212, 175, 106, 0.3));
            transition: all 0.3s ease;
        }

        .card:hover .card-icon {
            transform: scale(1.1) translateY(-5px);
            filter: drop-shadow(0 0 30px rgba(212, 175, 106, 0.5));
        }

        .card h3 {
            font-size: 1.5rem;
            margin-bottom: 1rem;
            color: var(--text-light);
        }

        .card p {
            color: var(--text-muted);
            line-height: 1.7;
        }

        /* Features */
        .features-grid {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 2rem;
        }

        .feature-card {
            display: flex;
            gap: 2rem;
            padding: 3rem;
            background: var(--card-bg);
            border: 2px solid transparent;
            background-image: linear-gradient(135deg, rgba(26, 77, 71, 0.15) 0%, rgba(42, 93, 87, 0.08) 100%), var(--border-gradient);
            background-origin: border-box;
            background-clip: padding-box, border-box;
            border-radius: 20px;
            transition: all 0.4s ease;
            position: relative;
            overflow: hidden;
        }

        .feature-card::after {
            content: '';
            position: absolute;
            top: 0;
            right: -50%;
            width: 50%;
            height: 100%;
            background: linear-gradient(90deg, transparent, rgba(212, 175, 106, 0.05));
            transform: skewX(-15deg);
            transition: right 0.5s ease;
        }

        .feature-card:hover::after {
            right: 100%;
        }

        .feature-card:hover {
            transform: translateX(5px);
            box-shadow: 0 10px 40px rgba(212, 175, 106, 0.2);
        }

        .feature-icon {
            font-size: 2.5rem;
            flex-shrink: 0;
        }

        .feature-content h3 {
            font-size: 1.5rem;
            margin-bottom: 0.75rem;
        }

        .feature-content p {
            color: var(--text-muted);
            line-height: 1.7;
        }

        /* Pricing */
        .pricing-grid {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 2rem;
            max-width: 1000px;
            margin: 0 auto;
        }

        .pricing-card {
            background: var(--card-bg);
            border: 2px solid transparent;
            background-image: linear-gradient(135deg, rgba(26, 77, 71, 0.15) 0%, rgba(42, 93, 87, 0.08) 100%), var(--border-gradient);
            background-origin: border-box;
            background-clip: padding-box, border-box;
            padding: 3rem;
            border-radius: 24px;
            transition: all 0.4s ease;
            position: relative;
            overflow: hidden;
        }

        .pricing-card::before {
            content: '';
            position: absolute;
            top: -100%;
            left: -100%;
            width: 300%;
            height: 300%;
            background: radial-gradient(circle, rgba(212, 175, 106, 0.1) 0%, transparent 60%);
            transition: all 0.8s ease;
        }

        .pricing-card:hover::before {
            top: -50%;
            left: -50%;
        }

        .pricing-card.featured {
            background-image: linear-gradient(135deg, rgba(26, 77, 71, 0.3) 0%, rgba(42, 93, 87, 0.15) 100%), 
                              linear-gradient(135deg, var(--accent-gold) 0%, var(--accent-gold-light) 100%);
            transform: scale(1.05);
            box-shadow: 0 20px 60px rgba(212, 175, 106, 0.3);
        }

        .pricing-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 20px 50px rgba(212, 175, 106, 0.25);
        }

        .pricing-card.featured:hover {
            transform: scale(1.05) translateY(-10px);
        }

        .pricing-card.featured::before {
            content: 'MOST POPULAR';
            position: absolute;
            top: 1.5rem;
            right: 1.5rem;
            background: linear-gradient(135deg, var(--accent-gold-light) 0%, var(--accent-gold) 100%);
            color: var(--deep-green);
            padding: 0.5rem 1rem;
            border-radius: 50px;
            font-size: 0.75rem;
            font-weight: 700;
            letter-spacing: 1px;
            box-shadow: 0 4px 15px rgba(212, 175, 106, 0.4);
            animation: none;
        }

        .pricing-header h3 {
            font-size: 2rem;
            margin-bottom: 1rem;
        }

        .price {
            font-size: 3rem;
            font-weight: 700;
            background: linear-gradient(135deg, var(--accent-gold-light) 0%, var(--accent-gold) 100%);
            -webkit-background-clip: text;
            background-clip: text;
            -webkit-text-fill-color: transparent;
            margin-bottom: 0.5rem;
            filter: drop-shadow(0 0 20px rgba(212, 175, 106, 0.3));
        }

        .price span {
            font-size: 1rem;
            color: var(--text-muted);
            font-weight: 400;
        }

        .pricing-features {
            list-style: none;
            margin: 2rem 0 3rem;
        }

        .pricing-features li {
            padding: 1rem 0;
            border-bottom: 1px solid;
            border-image: linear-gradient(90deg, transparent, rgba(212, 175, 106, 0.2), transparent) 1;
            display: flex;
            align-items: center;
            gap: 1rem;
            transition: all 0.3s ease;
        }

        .pricing-features li:hover {
            padding-left: 0.5rem;
            background: linear-gradient(90deg, rgba(212, 175, 106, 0.05), transparent);
        }

        .pricing-features li:last-child {
            border-bottom: none;
        }

        .pricing-features li::before {
            content: '✓';
            background: linear-gradient(135deg, var(--accent-gold-light) 0%, var(--accent-gold) 100%);
            -webkit-background-clip: text;
            background-clip: text;
            -webkit-text-fill-color: transparent;
            font-weight: 700;
            font-size: 1.25rem;
        }

        /* Process Steps */
        .steps-grid {
            display: grid;
            grid-template-columns: repeat(4, 1fr);
            gap: 2rem;
        }

        .step {
            text-align: center;
            position: relative;
            opacity: 0;
            transform: translateY(30px);
            animation: fadeInUpStagger 0.6s ease-out forwards;
        }

        .step:nth-child(1) { animation-delay: 0.1s; }
        .step:nth-child(2) { animation-delay: 0.2s; }
        .step:nth-child(3) { animation-delay: 0.3s; }
        .step:nth-child(4) { animation-delay: 0.4s; }

        @keyframes fadeInUpStagger {
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        .step-number {
            width: 80px;
            height: 80px;
            border-radius: 50%;
            background: linear-gradient(135deg, var(--accent-gold-light) 0%, var(--accent-gold) 100%);
            color: var(--deep-green);
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 2rem;
            font-weight: 700;
            margin: 0 auto 2rem;
            box-shadow: 0 10px 40px var(--accent-gold-glow);
            transition: all 0.4s ease;
            position: relative;
        }

        .step-number::before {
            content: '';
            position: absolute;
            inset: -3px;
            border-radius: 50%;
            background: linear-gradient(135deg, var(--accent-gold-light), var(--accent-gold));
            opacity: 0;
            transition: opacity 0.4s ease;
            z-index: -1;
        }

        .step:hover .step-number {
            transform: scale(1.1) rotate(5deg);
            box-shadow: 0 15px 50px var(--accent-gold-glow);
        }

        .step:hover .step-number::before {
            opacity: 0.5;
            animation: spin 3s linear infinite;
        }

        @keyframes spin {
            to { transform: rotate(360deg); }
        }

        .step h3 {
            font-size: 1.5rem;
            margin-bottom: 1rem;
        }

        .step p {
            color: var(--text-muted);
        }

        /* CTA Section */
        .cta-section {
            text-align: center;
            padding: 8rem 0;
            background: linear-gradient(135deg, rgba(26, 77, 71, 0.4) 0%, rgba(15, 46, 42, 0.6) 50%, rgba(10, 30, 27, 0.8) 100%);
            border: 2px solid transparent;
            background-image: linear-gradient(135deg, rgba(26, 77, 71, 0.4) 0%, rgba(10, 30, 27, 0.8) 100%), var(--border-gradient);
            background-origin: border-box;
            background-clip: padding-box, border-box;
            border-radius: 32px;
            margin: 4rem 2rem;
            position: relative;
            overflow: hidden;
        }

        .cta-section::before {
            content: '';
            position: absolute;
            top: -50%;
            left: 50%;
            transform: translateX(-50%);
            width: 800px;
            height: 800px;
            background: radial-gradient(circle, rgba(212, 175, 106, 0.25) 0%, transparent 70%);
            border-radius: 50%;
            filter: blur(100px);
            animation: float 15s ease-in-out infinite;
        }

        .cta-section::after {
            content: '';
            position: absolute;
            bottom: -30%;
            right: -10%;
            width: 600px;
            height: 600px;
            background: radial-gradient(circle, rgba(26, 77, 71, 0.3) 0%, transparent 70%);
            border-radius: 50%;
            filter: blur(80px);
            animation: float 20s ease-in-out infinite reverse;
        }

        .cta-section h2 {
            font-size: 4rem;
            margin-bottom: 1.5rem;
            position: relative;
            z-index: 2;
            background: linear-gradient(135deg, #ffffff 0%, var(--accent-gold-light) 100%);
            -webkit-background-clip: text;
            background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .cta-section p {
            font-size: 1.25rem;
            color: var(--text-muted);
            margin-bottom: 3rem;
            position: relative;
            z-index: 2;
        }

        /* Footer */
        footer {
            padding: 6rem 0 3rem;
            border-top: 1px solid var(--border-subtle);
        }

        .footer-content {
            display: grid;
            grid-template-columns: 2fr 1fr 1fr;
            gap: 4rem;
            margin-bottom: 4rem;
        }

        .footer-brand h3 {
            font-size: 1.5rem;
            background: linear-gradient(135deg, var(--accent-gold-light) 0%, var(--accent-gold) 100%);
            -webkit-background-clip: text;
            background-clip: text;
            -webkit-text-fill-color: transparent;
            margin-bottom: 1rem;
        }

        .footer-brand p {
            color: var(--text-muted);
            line-height: 1.7;
        }

        .footer-links h4 {
            margin-bottom: 1.5rem;
            color: var(--text-light);
        }

        .footer-links a {
            display: block;
            color: var(--text-muted);
            text-decoration: none;
            margin-bottom: 0.75rem;
            transition: all 0.3s ease;
            position: relative;
            padding-left: 0;
        }

        .footer-links a:hover {
            color: var(--accent-gold-light);
            transform: translateX(5px);
        }

        .footer-bottom {
            text-align: center;
            padding-top: 3rem;
            border-top: 1px solid var(--border-subtle);
            color: var(--text-muted);
            font-size: 0.9rem;
        }

        /* Mobile Menu */
        .mobile-toggle {
            display: none;
            flex-direction: column;
            gap: 6px;
            background: none;
            border: none;
            cursor: pointer;
        }

        .mobile-toggle span {
            width: 25px;
            height: 2px;
            background: var(--text-light);
            transition: all 0.3s ease;
        }

        /* Responsive */
        @media (max-width: 1024px) {
            .hero h1 { font-size: 3.5rem; }
            .section-header h2 { font-size: 2.5rem; }
            .cards-grid { grid-template-columns: repeat(2, 1fr); }
            .stats { grid-template-columns: repeat(2, 1fr); }
            .steps-grid { grid-template-columns: repeat(2, 1fr); }
        }

        @media (max-width: 768px) {
            .nav-links { display: none; }
            .mobile-toggle { display: flex; }
            .hero h1 { font-size: 2.5rem; }
            .hero-actions { flex-direction: column; }
            .cards-grid,
            .features-grid,
            .pricing-grid,
            .stats,
            .steps-grid { grid-template-columns: 1fr; }
            .pricing-card.featured { transform: scale(1); }
            .footer-content { grid-template-columns: 1fr; }
            .cta-section h2 { font-size: 2.5rem; }
            .section { padding: 4rem 0; }
        }

        /* Animations */
        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(30px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        .hero-content { 
            animation: fadeInUp 0.8s ease-out; 
        }

        /* Scroll Reveal Animation */
        .scroll-reveal {
            opacity: 0;
            transform: translateY(50px);
            transition: all 0.8s cubic-bezier(0.4, 0, 0.2, 1);
        }

        .scroll-reveal.revealed {
            opacity: 1;
            transform: translateY(0);
        }

        /* Gradient Border Animation */
        @keyframes borderGlow {
            0%, 100% { 
                border-image: linear-gradient(135deg, rgba(212, 175, 106, 0.3) 0%, rgba(26, 77, 71, 0.3) 100%) 1;
            }
            50% { 
                border-image: linear-gradient(135deg, rgba(212, 175, 106, 0.6) 0%, rgba(26, 77, 71, 0.6) 100%) 1;
            }
        }

        .animated-border {
            animation: borderGlow 3s ease-in-out infinite;
        }
    </style>
</head>
<body>
    <header>
        <nav>
            <div class="logo">BLACK PEAK</div>
            <ul class="nav-links">
                <li><a href="#services">Services</a></li>
                <li><a href="#pricing">Pricing</a></li>
                <li><a href="#process">Process</a></li>
                <li><a href="#about">About</a></li>
            </ul>
            <a href="https://wa.me/yournumber" class="btn btn-primary">Get Started</a>
            <button class="mobile-toggle">
                <span></span>
                <span></span>
                <span></span>
            </button>
        </nav>
    </header>

    <main>
        <section class="hero">
            <div class="container">
                <div class="hero-content">
                    <span class="badge">LEAD GENERATION EXPERTS</span>
                    <h1>Generate Qualified Leads That Convert</h1>
                    <p>We help local businesses scale with targeted Google & Meta ads that drive real results. No fluff, just measurable growth and qualified inquiries.</p>
                    <div class="hero-actions">
                        <a href="https://wa.me/yournumber" class="btn btn-primary">Book Free Strategy Call</a>
                        <a href="#process" class="btn btn-secondary">See How It Works</a>
                    </div>
                </div>
                <div class="stats">
                    <div class="stat-item">
                        <div class="stat-number">800+</div>
                        <div class="stat-label">Leads Generated</div>
                    </div>
                    <div class="stat-item">
                        <div class="stat-number">5K+</div>
                        <div class="stat-label">Ad Impressions</div>
                    </div>
                    <div class="stat-item">
                        <div class="stat-number">15+</div>
                        <div class="stat-label">Active Campaigns</div>
                    </div>
                    <div class="stat-item">
                        <div class="stat-number">98%</div>
                        <div class="stat-label">Client Satisfaction</div>
                    </div>
                </div>
            </div>
        </section>

        <section id="services" class="section">
            <div class="container">
                <div class="section-header">
                    <div class="section-label">WHO WE SERVE</div>
                    <h2>Built for Local Service Businesses</h2>
                    <p>We partner with businesses that need immediate results and are ready to scale</p>
                </div>
                <div class="cards-grid">
                    <div class="card">
                        <span class="card-icon">🏠</span>
                        <h3>Home Services</h3>
                        <p>Pest control, cleaning, HVAC, plumbing, and maintenance services looking to fill their schedule with local customers.</p>
                    </div>
                    <div class="card">
                        <span class="card-icon">🏥</span>
                        <h3>Medical Clinics</h3>
                        <p>Specialized clinics and medical centers seeking more patient bookings and consultations.</p>
                    </div>
                    <div class="card">
                        <span class="card-icon">🛠️</span>
                        <h3>Service Providers</h3>
                        <p>Local businesses that rely on direct contact to close sales and grow their monthly revenue.</p>
                    </div>
                </div>
            </div>
        </section>

        <section class="section" style="background: rgba(10, 61, 54, 0.1);">
            <div class="container">
                <div class="section-header">
                    <div class="section-label">WHAT WE DO</div>
                    <h2>Outcome-Driven Marketing</h2>
                    <p>Strategic campaigns designed for maximum conversion and measurable ROI</p>
                </div>
                <div class="features-grid">
                    <div class="feature-card">
                        <span class="feature-icon">🎯</span>
                        <div class="feature-content">
                            <h3>Google & Meta Ads</h3>
                            <p>Precision-targeted campaigns that connect you with customers actively searching for your services right now.</p>
                        </div>
                    </div>
                    <div class="feature-card">
                        <span class="feature-icon">💬</span>
                        <div class="feature-content">
                            <h3>WhatsApp Campaigns</h3>
                            <p>Direct messaging ads that initiate instant conversations with qualified prospects.</p>
                        </div>
                    </div>
                    <div class="feature-card">
                        <span class="feature-icon">📄</span>
                        <div class="feature-content">
                            <h3>Conversion Funnels</h3>
                            <p>High-converting landing pages optimized to turn clicks into qualified leads and bookings.</p>
                        </div>
                    </div>
                    <div class="feature-card">
                        <span class="feature-icon">📊</span>
                        <div class="feature-content">
                            <h3>Analytics & Optimization</h3>
                            <p>Weekly tracking and refinement to maximize your ROI and lower cost per acquisition.</p>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <section id="pricing" class="section">
            <div class="container">
                <div class="section-header">
                    <div class="section-label">PRICING</div>
                    <h2>Transparent Plans</h2>
                    <p>No hidden fees. Choose the package that matches your growth stage.</p>
                </div>
                <div class="pricing-grid">
                    <div class="pricing-card">
                        <div class="pricing-header">
                            <h3>Starter</h3>
                            <div class="price">AED 1,500–2,500<span>/month</span></div>
                        </div>
                        <ul class="pricing-features">
                            <li>Google Ads OR Meta Ads</li>
                            <li>WhatsApp click campaigns</li>
                            <li>Landing page setup</li>
                            <li>Weekly performance reports</li>
                            <li>Ad spend managed by client</li>
                        </ul>
                        <a href="https://wa.me/yournumber" class="btn btn-secondary" style="width: 100%;">Get Started</a>
                    </div>
                    <div class="pricing-card featured">
                        <div class="pricing-header">
                            <h3>Growth</h3>
                            <div class="price">AED 3,500–5,000<span>/month</span></div>
                        </div>
                        <ul class="pricing-features">
                            <li>Google + Meta Ads</li>
                            <li>Advanced retargeting</li>
                            <li>WhatsApp automation</li>
                            <li>Priority support</li>
                            <li>Lead tracking dashboard</li>
                        </ul>
                        <a href="https://wa.me/yournumber" class="btn btn-primary" style="width: 100%;">Scale Now</a>
                    </div>
                </div>
            </div>
        </section>

        <section id="process" class="section" style="background: rgba(10, 61, 54, 0.1);">
            <div class="container">
                <div class="section-header">
                    <div class="section-label">OUR PROCESS</div>
                    <h2>How We Drive Results</h2>
                    <p>A proven 4-step system to scale your inquiries and bookings</p>
                </div>
                <div class="steps-grid">
                    <div class="step">
                        <div class="step-number">1</div>
                        <h3>Launch Fast</h3>
                        <p>Campaigns live within days, not weeks. We focus on speed without sacrificing quality.</p>
                    </div>
                    <div class="step">
                        <div class="step-number">2</div>
                        <h3>Generate Leads</h3>
                        <p>Qualified calls and messages start flowing directly to your business.</p>
                    </div>
                    <div class="step">
                        <div class="step-number">3</div>
                        <h3>Track Performance</h3>
                        <p>Monitor every lead's cost and quality for maximum efficiency.</p>
                    </div>
                    <div class="step">
                        <div class="step-number">4</div>
                        <h3>Optimize Weekly</h3>
                        <p>Continuous refinement to improve results and reduce costs.</p>
                    </div>
                </div>
            </div>
        </section>

        <div class="container">
            <div class="cta-section">
                <h2>Ready to Scale Your Business?</h2>
                <p>Book your free strategy call today and discover how we can generate qualified leads for your business.</p>
                <a href="https://wa.me/yournumber" class="btn btn-primary btn-large">Book My Free Strategy Call</a>
            </div>
        </div>
    </main>

    <footer>
        <div class="container">
            <div class="footer-content">
                <div class="footer-brand">
                    <h3>BLACK PEAK DIGITAL</h3>
                    <p>Lead generation specialists helping local businesses scale through targeted digital advertising.</p>
                </div>
                <div class="footer-links">
                    <h4>Quick Links</h4>
                    <a href="#services">Services</a>
                    <a href="#pricing">Pricing</a>
                    <a href="#process">Process</a>
                </div>
                <div class="footer-links">
                    <h4>Contact</h4>
                    <a href="https://wa.me/yournumber">WhatsApp</a>
                    <a href="mailto:hello@blackpeak.digital">Email Us</a>
                </div>
            </div>
            <div class="footer-bottom">
                <p>&copy; 2024 Black Peak Digital. All rights reserved.</p>
            </div>
        </div>
    </footer>

    <script>
        // Smooth scrolling
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                if (target) {
                    target.scrollIntoView({ behavior: 'smooth', block: 'start' });
                }
            });
        });

        // Header scroll effect
        let lastScroll = 0;
        const header = document.querySelector('header');
        
        window.addEventListener('scroll', () => {
            const currentScroll = window.pageYOffset;
            
            if (currentScroll > 100) {
                header.classList.add('scrolled');
            } else {
                header.classList.remove('scrolled');
            }
            
            lastScroll = currentScroll;
        });

        // Scroll reveal animation
        const observerOptions = {
            threshold: 0.1,
            rootMargin: '0px 0px -100px 0px'
        };

        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.classList.add('revealed');
                }
            });
        }, observerOptions);

        // Add scroll-reveal class to elements
        document.querySelectorAll('.card, .feature-card, .pricing-card, .stat-item').forEach(el => {
            el.classList.add('scroll-reveal');
            observer.observe(el);
        });

        // Mobile menu toggle
        const mobileToggle = document.querySelector('.mobile-toggle');
        const navLinks = document.querySelector('.nav-links');

        if (mobileToggle) {
            mobileToggle.addEventListener('click', () => {
                navLinks.classList.toggle('active');
            });
        }
    </script>