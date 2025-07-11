# Daily Exercise Routine

**Your Complete Wellness Practice**  
*10-15 minutes • Daily practice • Total wellness*

---

## 1. Sit-to-Stand
- **Reps:** 10 repetitions
- **Equipment:** 5 lb dumbbells in each hand
- **Benefits:** Builds leg strength and functional mobility

## 2. Upper Body Circuit (Seated)
- **Equipment:** 5 lb dumbbells
- **Sequence:** 
  1. Bicep curl
  2. Overhead press
  3. Tricep extension (bend at elbow)
  4. Overhead press
  5. Lower to shoulder height
  6. Reverse curl to starting position
- **Benefits:** Complete upper body strength training

## 3. Seated Forward Fold
- **Movement:** Gentle forward bend while seated
- **Benefits:** Spinal mobility and lower back flexibility

## 4. Ankle Pumps
- **Reps:** 10-15 repetitions
- **Movement:** Flex feet up and down while seated
- **Benefits:** Improves circulation and reduces leg stiffness

## 5. Kapalabhati Breathing
- **Rounds:** A few rounds of skull-shining breath
- **Benefits:** Strengthens respiratory muscles and promotes mental clarity

---

> *"Small consistent actions create lasting change"*

**Daily Checklist:**
- [ ] Sit-to-Stand (10 reps)
- [ ] Upper Body Circuit
- [ ] Seated Forward Fold
- [ ] Ankle Pumps (10-15 reps)
- [ ] Kapalabhati Breathing

---

Copy and paste this prompt at the start of any new conversation to activate your personal exercise coach:

---

**EXERCISE COACH MODE - DAILY ROUTINE ASSISTANT**

You are my personal exercise coach helping me maintain daily consistency with my specific routine. I am a 67-year-old, 250-pound man with a 5-exercise routine that takes 10-15 minutes.

**MY ROUTINE:**
1. **Sit-to-Stand** - 10 reps with 5 lb dumbbells in each hand
2. **Upper Body Circuit** (seated with 5 lb dumbbells):
   - Bicep curl → Overhead press → Tricep extension → Overhead press → Lower to shoulders → Reverse curl
3. **Seated Forward Fold** - Gentle forward bend for spinal mobility  
4. **Ankle Pumps** - 10-15 reps flexing feet up and down
5. **Kapalabhati Breathing** - A few rounds of skull-shining breath

**YOUR ROLE:**
- When I say "let's begin" or similar, present my routine as a numbered menu
- Let me choose which exercise to do or if I want to do the full routine
- Provide brief encouragement and form reminders for each exercise
- Help me track progress and maintain daily consistency
- Be supportive but not overly chatty - keep responses focused and motivating
- Remind me of the benefits of each exercise when relevant

**COACHING STYLE:**
- Encouraging but practical
- Focus on consistency over intensity
- Acknowledge that some days will be easier than others
- Celebrate small wins and daily completion
- Provide gentle reminders about form and breathing

**RESPONSE FORMAT:**
When I'm ready to exercise, show me:
```
Ready for your daily routine! Choose an option:

1. Sit-to-Stand (10 reps)
2. Upper Body Circuit (seated)
3. Seated Forward Fold
4. Ankle Pumps (10-15 reps)
5. Kapalabhati Breathing
6. Complete Full Routine
7. Skip today (tell me why)

What would you like to do?
```

Remember: I value consistency over perfection. Your job is to help me show up daily, even if some days I only do one or two exercises.

---

**Instructions:** Copy this entire prompt and paste it at the beginning of a new conversation with Claude. Then simply say "let's begin" to start your coached workout session!


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Daily Exercise Routine</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            max-width: 600px;
            margin: 0 auto;
            padding: 20px;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
        }
        
        .routine-card {
            background: white;
            border-radius: 20px;
            padding: 30px;
            box-shadow: 0 20px 40px rgba(0,0,0,0.1);
            border: 3px solid #f0f0f0;
        }
        
        .header {
            text-align: center;
            margin-bottom: 30px;
        }
        
        .title {
            color: #2c3e50;
            font-size: 28px;
            font-weight: bold;
            margin-bottom: 10px;
        }
        
        .subtitle {
            color: #7f8c8d;
            font-size: 16px;
            margin-bottom: 20px;
        }
        
        .exercise-item {
            display: flex;
            align-items: center;
            margin-bottom: 20px;
            padding: 15px;
            background: #f8f9fa;
            border-radius: 12px;
            border-left: 5px solid #3498db;
            transition: all 0.3s ease;
        }
        
        .exercise-item:hover {
            transform: translateX(5px);
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
        }
        
        .exercise-number {
            background: #3498db;
            color: white;
            width: 35px;
            height: 35px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-weight: bold;
            margin-right: 20px;
            font-size: 18px;
        }
        
        .exercise-content {
            flex: 1;
        }
        
        .exercise-name {
            font-size: 18px;
            font-weight: bold;
            color: #2c3e50;
            margin-bottom: 5px;
        }
        
        .exercise-details {
            color: #7f8c8d;
            font-size: 14px;
            line-height: 1.4;
        }
        
        .breathing {
            border-left-color: #e74c3c;
        }
        
        .breathing .exercise-number {
            background: #e74c3c;
        }
        
        .footer {
            text-align: center;
            margin-top: 30px;
            color: #7f8c8d;
            font-style: italic;
        }
        
        .checkmark {
            margin-left: 10px;
            font-size: 20px;
            color: #27ae60;
            opacity: 0;
            transition: opacity 0.3s ease;
        }
        
        .exercise-item:hover .checkmark {
            opacity: 1;
        }
        
        @media print {
            body {
                background: white;
                min-height: auto;
            }
            .routine-card {
                box-shadow: none;
                border: 2px solid #ddd;
            }
        }
    </style>
</head>
<body>
    <div class="routine-card">
        <div class="header">
            <div class="title">Daily Exercise Routine</div>
            <div class="subtitle">Your Complete Wellness Practice</div>
        </div>
        
        <div class="exercise-item">
            <div class="exercise-number">1</div>
            <div class="exercise-content">
                <div class="exercise-name">Sit-to-Stand</div>
                <div class="exercise-details">10 repetitions with 5 lb dumbbells in each hand<br>
                Builds leg strength and functional mobility</div>
            </div>
            <div class="checkmark">✓</div>
        </div>
        
        <div class="exercise-item">
            <div class="exercise-number">2</div>
            <div class="exercise-content">
                <div class="exercise-name">Upper Body Circuit</div>
                <div class="exercise-details">While seated with 5 lb dumbbells:<br>
                Bicep curl → Overhead press → Tricep extension → Overhead press → Lower to shoulders → Reverse curl</div>
            </div>
            <div class="checkmark">✓</div>
        </div>
        
        <div class="exercise-item">
            <div class="exercise-number">3</div>
            <div class="exercise-content">
                <div class="exercise-name">Seated Forward Fold</div>
                <div class="exercise-details">Gentle forward bend for spinal mobility<br>
                Helps with posture and lower back flexibility</div>
            </div>
            <div class="checkmark">✓</div>
        </div>
        
        <div class="exercise-item">
            <div class="exercise-number">4</div>
            <div class="exercise-content">
                <div class="exercise-name">Ankle Pumps</div>
                <div class="exercise-details">10-15 reps flexing feet up and down<br>
                Improves circulation and reduces leg stiffness</div>
            </div>
            <div class="checkmark">✓</div>
        </div>
        
        <div class="exercise-item breathing">
            <div class="exercise-number">5</div>
            <div class="exercise-content">
                <div class="exercise-name">Kapalabhati Breathing</div>
                <div class="exercise-details">A few rounds of skull-shining breath<br>
                Strengthens respiratory muscles and promotes mental clarity</div>
            </div>
            <div class="checkmark">✓</div>
        </div>
        
        <div class="footer">
            "Small consistent actions create lasting change"<br>
            10-15 minutes • Daily practice • Total wellness
        </div>
    </div>
</body>
</html>
