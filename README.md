# WhatsApp — Clear by Date

> **Clear a day, not a decade.**

An independent UX/product concept exploring how WhatsApp could let users clear messages from a **specific day or date range** instead of removing the entire chat history.

🔗 **[Try the interactive prototype](https://saisatwikak.github.io/Whatsapp_feature_idea/)**

---

## 💡 The Problem

Clearing a WhatsApp chat can feel like an all-or-nothing decision.

Sometimes a user may want to remove messages from a particular period while keeping the rest of the conversation intact.

For example:

> "I want to remove the messages from one particular week, but keep everything else."

The existing experience does not provide this level of date-based control.

This concept explores a middle ground between:

- Keeping the entire chat history
- Clearing the entire chat history

### Design question

**What if users could clear a specific day or date range while keeping the rest of their chat history?**

---

## 🎯 The Concept

**Clear by Date** introduces a new option within the existing Clear Chat flow.

Instead of only choosing to clear everything, the user can:

1. Choose **a day or a range of days**
2. Review exactly what will be removed
3. See an estimated message and storage count
4. Confirm the action
5. Temporarily undo the action

The goal is to give users **more control without creating an entirely new interaction pattern.**

---

## 🔄 User Flow

```text
Chat
  ↓
⋮ Overflow Menu
  ↓
More
  ↓
Clear Chat
  ↓
Choose what to remove
  ↓
A day or a range of days
  ↓
Select dates
  ↓
Review selection
  ↓
Confirm
  ↓
Messages cleared
  ↓
Undo

---

## 🎯 The Concept

**Clear by Date** introduces a new option within the existing Clear Chat flow.

Instead of only choosing to clear everything, the user can:

1. Choose **a day or a range of days**
2. Review exactly what will be removed
3. See an estimated message and storage count
4. Confirm the action
5. Temporarily undo the action

The goal is to give users **more control without creating an entirely new interaction pattern.**

---

## ✨ Key UX Decisions

### 1. Date-based clearing

Users can select:

- A single day
- A custom date range
- Quick selections such as **Yesterday** or **Last 7 Days**

A calendar provides a visual way to understand the selected period.

### 2. Explicit confirmation

Before clearing messages, the prototype shows:

- Selected date range
- Number of messages
- Photos
- Videos
- Documents
- Estimated storage freed

This makes the consequence of the action more visible before confirmation.

### 3. Local-only deletion

The concept is designed around **"delete for me"** behavior.

The selected messages are removed from the user's device while the other participant keeps their own copy.

### 4. Undo

A short-lived Undo action is provided immediately after clearing.

The concept specification uses a **30-second Undo window**. The current prototype demonstrates the interaction with a shorter demo timeout.

### 5. History marker

After clearing, the chat includes a system message indicating that messages from a particular period were cleared.

This helps explain gaps in the conversation instead of making the missing history look like a loading or synchronization problem.
