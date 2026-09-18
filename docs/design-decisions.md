# Design Decisions

This concept was designed around giving users more control over what part of their chat history they want to clear, while keeping the interaction familiar and understandable.

## 1. Date-Based Clearing

The core idea is to introduce a middle option between:

- Keeping the entire conversation
- Clearing the entire conversation

The proposed **Clear by Date or Range** option allows users to remove only the history they select.

## 2. One-to-One Chats for V1

The first version is scoped to one-to-one chats.

Group chats are left for separate consideration because shared conversation history introduces additional product and interaction considerations.

## 3. Local-Only Deletion

The proposed behavior is based on **local deletion**.

The selected messages are removed from the user's own chat history rather than introducing a "delete for everyone" behavior.

## 4. Explicit Confirmation

Clearing messages is a destructive action, so the selected date or range is shown clearly before the user confirms.

This helps the user understand exactly what portion of the conversation they are about to remove.

## 5. Undo

A short Undo window is included after the clearing action.

The concept specifies a **30-second Undo period**, providing a recovery opportunity if the user clears the wrong range accidentally.

## 6. Media Handling

Media associated with messages inside the selected range is also considered as part of the clearing behavior.

The concept distinguishes chat-linked media from files that may already exist independently in the phone's gallery or downloads.

## 7. Cleared-History Marker

After clearing, a system marker indicates where the conversation history was cleared.

This helps explain a gap in the conversation instead of making the missing history appear unexplained.

## 8. Familiar Entry Point

The feature is introduced through the existing chat-clearing path:

**Chat → ⋮ → More → Clear Chat**

This keeps the proposed interaction connected to an action users already understand.

## 9. Progressive Rollout

The concept also considers a feature-flag approach for implementation:

1. Enable the feature for a small percentage of users.
2. Monitor behavior and support issues.
3. Gradually expand availability based on observations.
